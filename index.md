**Halo Sport** - Neurostimulator that targets the motor cortex, priming neurons for increased muscle memory and training.  I architected and engineered the Android app from the ground up, leveraging RxJava to produce a highly responsive UX.  I also built a low-loss time series hardware analytics system that spans the entire vertical software stack, implementing an analytics flash storage system on the Halo Sport headset that can store up to 3600 analytics records that get routed via the Halo Sport mobile apps to AWS Kinesis Firehose and ultimately stored in a Redshift database.  Once in Redshift, I developed a set of Python scripts to perform ETL and data mining for internal analytics.

Learn more at https://www.haloneuro.com and download the app on [Google Play](https://play.google.com/store/apps/details?id=com.haloneuro.halo)

**Kindara Wink** - Accurate and precise Bluetooth LE thermometer automatically syncs temperatures to Kindara’s Android and iOS apps.  As the Lead Engineer at Kindara, I was directly responsible for Wink, engineering embedded-C firmware and Bluetooth LE integrations for both Android and iOS (painfully integrated via Cordova on Android).  Additionally, I spent a fair amount of time on the workbench stress testing Wink and analyzing power consumption and sleep states.  Wink is now a successful connected device with over 10,000 shipped devices.

Learn more at https://kindara.com/wink and download the apps on [Google Play](https://play.google.com/store/apps/details?id=com.kindara.pgap) and the [App Store](https://itunes.apple.com/us/app/kindara-fertility-awareness/id522674372?mt=8)

**Aerovironment ProCore** - In-depth interface for configuring electric forklifts via Bluetooth LE with over a hundred commands and settings.  API developed using Java generics.  I was responsible for the entire BLE Api and generic interfaces for the command set and guided UX development done by junior engineers.  

Learn more at http://www.posicharge.com/procore and download the app on [Google Play](https://play.google.com/store/apps/details?id=com.aerovironment.ngc&hl=en)

**Zymurgy** - Magazine app provides seamless online and offline access and searching capabilities to the entire PDF archive of the American Homebrewer Association’s flagship publication, Zymurgy.  I hacked apart MuPDF - an outstanding LGPL PDF library for built for the Android NDK - and added chrome around it to provide searching capabilities and other specifics requested by the AHA.  

Download the app on [Google Play](https://play.google.com/store/apps/details?id=com.zymurgy)

**IDB Gallery** - Award-winning iPad app presents a virtual gallery of the IDB’s art collection, served from a RESTful Web Api.  User can search the art collection via a graphical world-map interface, where the user can zoom into the map and tap a country to view artwork for that country.  All content in the app is customizable via a custom CMS backend.

Download the app on the [App Store](https://itunes.apple.com/us/app/idb-gallery/id619335890) (no longer available in the U.S.)

**E-LRN** - Electronic learning system provides a Web 2.0 interface to the World Bank’s operational lessons database, complete with Lucene full-text indexing and geographic search functions.  The searching capabilities provide over 40 different filtering criteria.  The user can display search results either in list format or geographically mapped via Google Maps, as each lesson has geolocation metadata associated with a country.  Each user has a profile where they can save their favorite searches, lessons, and add comments and tags to those lessons.
