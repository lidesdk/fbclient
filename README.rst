fbclient
========

.. code-block::

 author : cosmin.apreutesei@gmail.com
 version: 0.5.0
 website: cosmin.apreutesei@gmail.com
 
A collection of pure Lua modules that allows you to connect and execute
queries against the Firebird Relational Database.
It is a modular, 3-layer interface, aiming at full API coverage.

===============  ==========  ==============
  platform          arch        version
===============  ==========  ==============
  ``Windows``      ``x86``      ``0.5.0``
  ===============  ==========  ==============

----------------------------------------------------------------------------------------------------

- 3-layer API: object interface, procedural interface, and binding
- written in Lua, all binding goes through alien
- aims at full API coverage, including the latest Firebird API additions
- decimals of up to 15 digits of precision with only Lua numbers
- full 64bit integer and decimal number support through bignum libraries
- multi-database transactions
- blobs, both segmented blobs and blob streams
- info API: info on databases, transactions, statements, blobs, etc.
- error reporting API
- service manager API: remote backup & restore, repair, user management, etc.
- binding to multiple client libraries in the same application/process
- tested against all Firebird 2.0, 2.1 and 2.5 releases on 32bit Windows and Linux (test suite included).

----------------------------------------------------------------------------------------------------


Dependencias
============
	
	* alien  0.4.1.53-1 
	* loop 1.4-1

Installation
===========

fbclient is included on stable repo.

.. code-block:: bash
	
	$ lide install fbclient


