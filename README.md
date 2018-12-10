# Modal-Popup
Using AngularJS Directives to display popup
A simple example to show how Angular JS directives work. 

Sample 1: Sample.aspx uses a directive "accomodations" that lists Accomodations such as Hotel, Home etc. These accomodations for now are defined in sampleController. You can optionally fetch data from a service. The accomodations are shown as buttons which when selected will display on UI back with comma separated values. The "accomodations" directive uses another directive "displayList" that renders the accomodations as buttons. It makes use of a callback function (& isolated scope) to display selected values on UI.

Sample 2: MaterialsPage.aspx uses a directive "materials". The directive displays Home accomodations. These accomodations are defined in sampleService.js and retrieved in materialsController.js.  The directive is shown in a popup modal. When you select an accomodation, you get a list of materials under the Accomodation. These materials are retrieved from sampleService.js. The service configures the various accomodations and materials. Alternatively, we can write Web API and retrieve results from the API. When you close the modal popup, all selected details are shown in MaterialsPage ASPX.

Project uses AngularJS service and directive concept and a bit of Underscore JS
