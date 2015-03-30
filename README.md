#Esri Polymer  

This project has turned Esri ArcGIS JavaScript web maps and asscociated elements into web components that can be used to create maps decleratively to HTML. It leverages Googles Polymer library which allows users to create custom web components.

The code also includes examples of how to make use of Polymer's two way databindings, observing changes to zoom level and extent and representing this as inputs on the map which can be changed.

It currently supports:

* esri-map - Attributes: basemap, zoom, centerLng, centerLat, webMapId (you can use a web map ID to pull through a map)

* esri-featurelayer - Attributes: featurelayer (the feature service url)

* esri-marker - Attributes: lat, lng

    * esri-marker-title - Attributes: none -  text goes between tags

    * esri-marker-content - Attributes: none - text goes between tags 

![Esri Polymer Screenshot](https://raw.githubusercontent.com/JamesMilnerUK/esri-polymer/master/screenshot.png "Esri Polymer Screenshot")

#Getting Started

An example of using esri-polymer is shown in the esri-polymer.html page in the repository. 

#Live Demo

You can see a live demo [here](http://appsstage.esriuk.com/app/developerevangelist/93/wmt/view/d147785761984557b69c73adf4a8e2da/esri-polymer/esri-polymer.html "Esri Polymer Live Demo")

It displays one web map constructed using attributes (basemap, zoom, etc), with a feature layer web component nested inside it and a second map constructed with a web map ID.

#Resources

- [Polymer Offical](https://www.polymer-project.org/0.5/ "Polymer Offical")
- [Polymer Developer Guide](https://www.polymer-project.org/0.5/docs/polymer/polymer.html "Polymer Developer Guide")
- [Polymer in 10 minutes](https://www.polymer-project.org/0.5/docs/start/creatingelements.html "Polymer in 10 minutes")
- [ArcGIS JavaScript API](https://developers.arcgis.com/javascript/jsapi/ "Esri ArcGIS JavaScript API")
- [ArcGIS for Developers](https://developers.arcgis.com/ "ArcGIS for Developers")
- [A Guide to Web Components](https://css-tricks.com/modular-future-web-components/ "A guide to web components")
- [webcomponents.js](https://github.com/webcomponents/webcomponentsjs "webcomponents.js")
- [Stackoverflow - Polymer](http://stackoverflow.com/search?q=polymer "Stackoverflow - Polymer")

#Issues

Find a bug or want to request a new feature? Please let us know by submitting an issue. Thank you!

#Contributing

Anyone and everyone is welcome to contribute. Please see our guidelines for contributing.

#Licensing

Copyright 2015 Esri UK

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0
Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

A copy of the license is available in the repository's LICENSE file.
