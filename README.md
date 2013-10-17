datamanager
===========

Data Manager is a browser based data management tool.

Data Manager is written entirely in JavaScript:
  * Makes extensive use of IndexedDB on the client for data persistence
  * Plan to incorporate canvas for graphics
  * NodeJS used on server
  * Server side-storage will initially be supported in MongoDB, but may add support for other dbs
  * Communication between client and server is done via websockets using the Socket.IO library
  * JSON objects are used as communication medium
  * Code is intended to be as non-blocking/asynchronous as possible

Overview of features:
  * Provides users with some database/programming knowledge the framework to rapidly create data driven web applications
  * WYSWIG/drag-and-drop editor for creating data collection and reporting templates
  * Automated creation of both the client-side and server-side data models
  * Persistence of data on the client will allow for complete offline functionality
  * Automated system for synching client and server data
  * Multi-level security model allowing users to control read/write access to the data