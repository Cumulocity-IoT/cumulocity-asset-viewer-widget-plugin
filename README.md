# Cumulocity Asset Viewer Widget Plugin [<img width="35" src="https://user-images.githubusercontent.com/67993842/97668428-f360cc80-1aa7-11eb-8801-da578bda4334.png"/>](https://github.com/SoftwareAG/cumulocity-asset-viewer-widget-plugin/releases/download/1.0.0-beta/asset-viewer-runtime-widget-1.0.0-beta.zip)

The Asset Viewer Widget is the Cumulocity module federation plugin created using c8ycli. This plugin can be used in Application Builder or Cockpit.
The Cumulocity Asset Viewer Widget help you to display assets/devices data in Tile/Grid view, along with navigation to template dashboards(App Builder only). This widget plugin also supports various features such as display child devices/assets, configuration of fields/columns, search, display only assets/devices where attentions required, server side pagination, etc.

### Please note that this plugin is in currently under BETA mode.

### Please choose Asset Viewer Widget release based on Cumulocity/Application builder version:

|APPLICATION BUILDER | CUMULOCITY | ASSET VIEWER WIDGET PLUGIN  |
|--------------------|------------|-----------------------------|
| 2.0.x(coming soon) | >= 1016.x.x| 1.x.x                       |

![Asset-Viewer](https://user-images.githubusercontent.com/99970126/169486721-aae8ec50-4eb5-4ae6-ae99-b2da57240e2e.jpg)
## Features
  
*  **Display Assets/Devices:** Displays Assets/Devices for give group in Tile/Grid mode. It also supports child devices/assets.

*  **Pagination:** Configurable Paginations and also option to set default page size.

*  **Configurable Columns:** User can choose what to display in each page of tiles from available list and also option to display custom field.

*  **Dashboard Settings (App Builder only):** Ability to navigate to dashboard by providing dashboard Id.

*  **Custom Images:**  Select and upload custom image to display in all tiles.  

*  **Attentions only:** Unique feature to display only assets/devices which are in high risk or have critical/major alerts. 


## Installation

## Prerequisites:
   Cumulocity c8ycli >=1016.x.x

### Runtime Deployment?

* This widget support runtime deployment. Download [Runtime Binary](https://github.com/SoftwareAG/cumulocity-asset-viewer-widget-plugin/releases/download/1.0.0-beta/asset-viewer-runtime-widget-1.0.0-beta.zip) and install via Administrations(Beta mode) --> Ecosystems --> Applications --> Packages 

### Local Development?

**Requirements:**
* Git
* NodeJS (release builds are currently built with `v14.18.0`)
* NPM (Included with NodeJS)

**Instructions**
1. Clone the repository: 
```
git clone https://github.com/SoftwareAG/cumulocity-asset-viewer-widget-plugin.git
```
2. Change directory: 
```
cd cumulocity-asset-viewer-widget-plugin
```
3. Install the dependencies: 
```
npm install
```
4. (Optional) Local development server: 
```
npm start -- --shell cockpit
```
5. Build the app: 
```
npm run build
```
6. Deploy the app: 
```
npm run deploy
```


------------------------------

These tools are provided as-is and without warranty or support. They do not constitute part of the Software AG product suite. Users are free to use, fork and modify them, subject to the license agreement. While Software AG welcomes contributions, we cannot guarantee to include every contribution in the master project.
_____________________
For more information you can Ask a Question in the [TECH Community Forums](https://tech.forums.softwareag.com/tag/Cumulocity-IoT).
