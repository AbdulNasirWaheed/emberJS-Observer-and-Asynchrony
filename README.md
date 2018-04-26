# emberJS-Observer-and-Asynchrony
Observers are synchronous in Ember.js, which fires immediately when one of the property of an observer gets updated

open the app.js file and add the following line at the top of the file −

import observerasynchrony from './observerasynchrony';
Where, observerasynchrony is a name of the file specified as "observerasynchrony.js" and created under the "app" folder.

Next, call the inherited "observerasynchrony" at the bottom, before the export. It executes the observerasynchrony function, 
which is created in the observerasynchrony.js file −

observerasynchrony();

Only observerasynchrony.js file included in this Repository
