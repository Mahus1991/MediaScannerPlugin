cordova-mediascanner-plugin
===========================

Simple Plugin to Scan File after it has been added to show up in Explorer.


How to Use
===========================

       window.plugins.scanmedia.scanFile(nativeURL,
                               function (result) {
                                   console.log(result);
                               }, function (error) {
                                   console.log(error);
                               });
