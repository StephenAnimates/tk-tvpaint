# Flow Production Tracking Toolkit (ShotGrid) for TVPaint Animation: tk-tvpaint engine

-------------------------------------------------------------------------
The Flow Production Tracking (ShotGrid) Toolkit for TVPaint
-------------------------------------------------------------------------

This repository is intended as a Flow Production Tracking Toolkit for TVPaint Animation.
The project is based on the Flow Production Tracking Toolkit default configuration
which provides TVPaint interoperability with Flow Production Tracking (ShotGrid).

The code is up-to-date with the tk-config-default2 configuration. The TVPaint engine
is a fork of the tk-config-default2 with some workflows specific for working with Flow
Production Tracking Toolkit.

[![Build Status](https://dev.azure.com/shotgun-ecosystem/Toolkit/_apis/build/status/Configs/tk-config-default2?branchName=master)](https://dev.azure.com/shotgun-ecosystem/Toolkit/_build/latest?definitionId=49&branchName=master)

Development information
- [Information and documentation about **Flow Production Tracking** (ShotGrid) integrations](https://help.autodesk.com/view/SGSUB/ENU/)

For more information, go to the following url:
https://help.autodesk.com/view/SGDEV/ENU/?guid=SGD_pg_integrations_admin_guides_integrations_admin_guide_html

-------------------------------------------------------------------------

To use tk-config-to paint, follow these steps:

1. In the Flow Production Tracking site, click the Avatar icon (top right) and select Default Layouts > Pipeline Configuration > Pipeline Configuration List
2. Click the Add Pipeline Configuration to create a new configuration
3. Set the **Plugin Ids** field to "basic.*"
4. Set the **Descriptor** field to match the desired version of the configuration
 - sgtk:descriptor:github_release?repository=tk-config-tvpaint
5. Launch Flow Production Tracking Desktop (Shotgun app)
6. Choose a project
7. Click the arrow in the top right and choose the new configuration
   
