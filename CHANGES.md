CHANGELOG
=========

1.1.1-dev
---------
* add `boundary` parameter to `Content-Type` header for `multipart/alternate` messages
* ensure correct order of mime-parts generated by `PlaintextMessage` plugin (HTML part should be at the end)

1.1.0 (2014-06-19)
------------------
* added autoload config in module class (ojhaujjwal)
* Sendmail is now default transport (ojhaujjwal)
* allow replacing Message object during e-mail composition (ojhaujjwal)
* automatically set Content-Type header to "multipart/alternative" when both HTML and plaintext versions
  are provided
* text body is added before HTML version (traedamatic)

1.0.0 (2014-04-23)
------------------

* tagged first stable version

