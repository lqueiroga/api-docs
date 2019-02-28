.. Copyright FUJITSU LIMITED 2019

.. _credaccountoutscale-object:

CredAccountOutscale
===================

A ``CredAccountOutscale`` object holds specific account information for the Outscale cloud platform.

Attributes
~~~~~~~~~~

The list of attributes for ``CredAccountOutscale`` are:

	* ``accessKeyId`` (string): the access key to use
	* ``accountNumber`` (string): the account number to use
	* ``keyPairName`` (string): the key pair name to use
	* ``secretAccessKeyId`` (string): the secret access key to use
	* ``name`` (string): the name of the cloud account
	* ``parentUri`` (anyURI): the uri resource of the parent object this cloud account is attached to
	* ``uri`` (anyURI): the uri resource of this cloud account
	* ``targetPlatform`` (:ref:`targetPlatform-object`): the target platform (see :ref:`targetplatform-object`) this cloud account is for
	* ``secretsMissing`` (boolean): a boolean flag to indicate that the secrets of this credAccount are missing and left empty in this object
	* ``created`` (dateTime): the date the appliance template is created
	* ``dbId`` (long): the database id of the object
	* ``digest`` (string): the digest value (used for etag)
	* ``lastModified`` (dateTime): the last modified date of this object


