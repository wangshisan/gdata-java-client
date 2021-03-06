This project is moved from
[googlecode](https://code.google.com/p/gdata-java-client/). Wikis are now kept in branch 'wiki'.
Issues are all migrated, too.

Older Google Data (GData) APIs use XML as their underlying format, but most Google APIs have released newer versions of their APIs based on JSON. You should migrate your code to use the new API infrastructure that is based on JSON. Likewise, if you have an existing application that uses the GData Java client library, you need to update your code to use the [Google APIs Client Library for Java](https://code.google.com/p/google-api-java-client/), as described on the [migration](https://code.google.com/p/gdata-java-client/wiki/MigratingToGoogleApiJavaClient) page.

We have stopped actively developing the GData Java client library, and the following table shows the GData status of relevant Google APIs:

| **API** | **GData Status** | **See Also** |
|:--------|:-----------------|:-------------|
| Google Analytics Data Export API | Shut down. Replaced by [Google Analytics Core Reporting API](https://developers.google.com/analytics/devguides/reporting/core/v3/) (starting at version 2.4). | [Migration Guide: Moving from v2.3 APIs to v2.4 & v3.0](https://developers.google.com/analytics/devguides/reporting/core/v2/migration-guide) |
| Google Apps Provisioning API | Deprecated as of May 2013, but continues to work as per [deprecation policy](https://developers.google.com/google-apps/admin-api-terms). Replaced by the [Admin SDK Directory API](https://developers.google.com/admin-sdk/directory/). | [Google Apps Provisioning API (Deprecated)](https://developers.google.com/google-apps/provisioning/) |
| Google Base Data API | Not available since June 1, 2011. Replaced by Shopping APIs. | [New Shopping APIs and Deprecation of the Base API](http://googlemerchantblog.blogspot.com/2010/12/new-shopping-apis-and-deprecation-of.html) |
| Blogger Data API | Replaced by the [latest Blogger API](https://developers.google.com/blogger/). |  |
| Google Book Search API | Shut down. Replaced by [Google Books API Family](https://developers.google.com/books/). | [Google books API searching by ISBN](http://stackoverflow.com/questions/7908954/google-books-api-searching-by-isbn) (on Stack Overflow) |
| Google Calendar API | Deprecated. Replaced by [Google Calendar API](https://developers.google.com/google-apps/calendar/). |  |
| Google Code Search Data API | Shut down in Jan 15, 2012. No replacement API. | [A fall sweep](http://googleblog.blogspot.com/2011/10/fall-sweep.html) (Google blog post) |
| Google Contacts API | Deprecated as of April 20, 2012, but continues to work as per [deprecation policy](https://developers.google.com/google-apps/contacts/v3/terms). Replaced by the [latest Google Contacts API](https://developers.google.com/google-apps/contacts/). | [Google Contacts API v2 Developer's Guide - Java](https://developers.google.com/google-apps/contacts/v2/developers_guide_java) |
| Google Documents List Data API |Deprecated as of Sep 14, 2012, but continues to work as per [deprecation policy](https://developers.google.com/google-apps/documents-list/terms). Replaced by [Google Drive API](https://developers.google.com/drive/). | [Google Documents List API version 3.0](https://developers.google.com/google-apps/documents-list/) |
| Google Finance Portfolio Data API | Deprecated as of June 3, 2011, but no scheduled shutdown date. No replacement API. | [Spring cleaning for some of our APIs](http://googlecode.blogspot.com/2011/05/spring-cleaning-for-some-of-our-apis.html) (Google blog post) |
| Google Health Data API | The product was [discontinued](https://www.google.com/intl/en_us/health/about/) as of January 1, 2013. No replacement API. | [An update on Google Health and Google PowerMeter](http://googleblog.blogspot.com/2011/06/update-on-google-health-and-google.html) |
| Google Maps Data API | Deprecated. Replaced by [Google Maps API Web Services](https://developers.google.com/maps/documentation/webservices/). |  |
| Picasa Web Albums Data API | GData version is still live. No replacement API. | [Client Libraries and Sample Code](https://developers.google.com/picasa-web/code) for Picasa Web Albums Data API |
| Google Project Hosting Issue Tracker API | Shut down on June 14, 2013. No replacement API. | [Winter cleaning](http://googleblog.blogspot.com/2012/12/winter-cleaning.html) (Google blog post) |
| Google Sidewiki Data API | Product discontinued. No replacement API. | [A fall spring-clean](http://googleblog.blogspot.com/2011/09/fall-spring-clean.html) (Google blog post) |
| Google Sites Data API | GData version is still live. No replacement API. | [What is the Google Sites API?](https://developers.google.com/google-apps/sites/) |
| Google Spreadsheets Data API | GData version is still live. No replacement API. | [Google Sheets API](https://developers.google.com/google-apps/spreadsheets/) |
| Google Translator Toolkit Data API | The API is now [restricted](https://developers.google.com/translator-toolkit/), but you can request access to the documentation. | [Google Translate API](https://cloud.google.com/translate/docs) |
| Google Webmaster Tools Data API | Not updated. Replaced by the [latest Webmaster Tools API](https://developers.google.com/webmaster-tools/). | [Quickstart: Run a Webmaster Tools App in Java](https://developers.google.com/webmaster-tools/v3/quickstart/quickstart-java) |
| YouTube Data API  | Deprecated in March 4, 2014, but continues to work as per [deprecation policy](https://developers.google.com/youtube/terms#deprecation). Replaced by [YouTube Data API (v3)](https://developers.google.com/youtube/v3/). | [YouTube Data API Migration Guide](https://developers.google.com/youtube/2.0/migration) |

**Android support:**
If you are developing for Android and the Google API you want to use is included in the [Google Play Services library](https://developer.android.com/google/play-services/index.html), you should use that library for the best performance and experience. If the Google API you want to use with Android is not part of the Google Play Services library, you can use the [Google APIs Client Library for Java](https://code.google.com/p/google-api-java-client/), which supports Android 1.5 (or higher) and provides other features such as OAuth 2.0 and Maven.
