Welcome to Django OIDC Provider Documentation!
==============================================

This tiny (but powerful!) package can help you providing out of the box all the endpoints, data and logic needed to add OpenID Connect capabilities to your Django projects. And as a side effect a fair implementation of OAuth2.0 too. Covers Authorization Code, Implicit and Hybrid flows.

Also implements the following specifications:

* `OAuth 2.0 for Native Apps <https://tools.ietf.org/html/draft-ietf-oauth-native-apps-01>`_
* `Proof Key for Code Exchange by OAuth Public Clients <https://tools.ietf.org/html/rfc7636>`_
* `Front-Channel Logout (draft 01) <http://openid.net/specs/openid-connect-frontchannel-1_0.html>`_

--------------------------------------------------------------------------------

Before getting started there are some important things that you should know:

* Despite that implementation MUST support TLS. You can make request without using SSL. There is no control on that.
* Supports only for requesting Claims using Scope values.

--------------------------------------------------------------------------------

Contents:

.. toctree::
   :maxdepth: 2

   sections/installation
   sections/relyingparties
   sections/serverkeys
   sections/templates
   sections/claims
   sections/userconsent
   sections/oauth2
   sections/logout
   sections/settings
   sections/examples
   sections/contribute
..

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
