Open ID
================================


InterMine web-applications allow users to create accounts and sign in to these accounts by authenticating with a selection of Open-ID providers, including Google and Yahoo.

To sign in with one of these authentication providers:
  1. Click on '''login''' (in the upper-right).
  1. Click the name of the Open-ID provider you wish to use.
  1. Authenticate yourself with your provider.
  1. You will be redirected to your mine when finished.

To set this up for a mine you administer:
  * The most important thing is to set up a couple of properties correctly
    in your mine's properties file (located in the `.intermine` directory), eg:

.. code-block:: properties

    webapp.baseurl=http://beta.flymine.org
    webapp.path=intermine-test

If you do not wish to allow Open-ID accounts, set the property "openid.allowed=false" in any of the property files that end up in the WEB_PROPERTIES map.

.. index:: Open ID, GMail, Yahoo, Google, myid.net
