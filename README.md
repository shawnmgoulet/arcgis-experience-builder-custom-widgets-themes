# ArcGIS Experience Builder Custom Widgets & Themes Repo

An Experience Builder custom widgets and themes sample repo.

## What's important

1. The key to the repo is that at it's root, it has a `manifest.json` file. The below properties (within this repo's `manifest.json`) are necessary for your repo to be integrated in your development environment's `client` directory and its webpack compile. Comments pertaining to necessary properties and values are included below.

```json
{
  "name": "exb-custom-widgets-themes-repo", // Required property
  "type": "exb-web-extension-repo", // Required property/value for the repo to be compiled by webpack within client
  "description": "This is a sample custom widgets and themes repo for the developer edition of ArcGIS Experience Builder.", // Required property
  "copyright": "", // Required property
  "license": "http://www.apache.org/licenses/LICENSE-2.0" // Required property
}
```

2. Within your repo, any custom widgets must live within a `widgets` child directory. Similarly, any custom themes must live within a `themes` child directory.
