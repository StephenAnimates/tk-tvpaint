# Flow Production Tracking Toolkit (ShotGrid) for TVPaint Animation: tk-config-tvpaint engine

-------------------------------------------------------------------------
The Flow Production Tracking (ShotGrid) Toolkit for TVPaint
-------------------------------------------------------------------------

This repository is intended as a Flow Production Tracking Toolkit for TVPaint Animation.
The project is based on the Flow Production Tracking Toolkit default configuration
which provides TVPaint interoperability with Flow Production Tracking (ShotGrid).

The TVPaint engine is a fork of the tk-config-default2 with some workflows specific for working with the Flow Production Tracking Toolkit with TVPaint

[![Build Status](https://dev.azure.com/shotgun-ecosystem/Toolkit/_apis/build/status/Configs/tk-config-default2?branchName=master)](https://dev.azure.com/shotgun-ecosystem/Toolkit/_build/latest?definitionId=49&branchName=master)

Development information
- [Information and documentation about **Flow Production Tracking** (ShotGrid) integrations](https://help.autodesk.com/view/SGSUB/ENU/)

For more information, go to the following url:
https://help.autodesk.com/view/SGDEV/ENU/?guid=SGD_pg_integrations_admin_guides_integrations_admin_guide_html

-------------------------------------------------------------------------

To use tk-config-tvpaint, follow these steps:

1. In the **Flow Production Tracking** site, click the Avatar icon (top right) and select Default Layouts > Pipeline Configuration > Pipeline Configuration List
1. Click the **Add Pipeline Configuration** button to create a new configuration
1. In the **Create a new Pipeline Configuration**, enter "tk-config-tvpaint" as the Pipeline Configuration Name
1. Set the **Plugin Ids** field to "basic.*"
1. Set the **Descriptor** field to match the desired version of the configuration: sgtk:descriptor:github_release?repository=tk-config-tvpaint
1. If needed, in the **Project** entry, add a specific project that the configuration will apply, all others will be ignored - no entry will make the configuration apply to all projects
1. Click the **Create Pipeline Configuration** button
1. Launch the Flow Production Tracking Desktop (Shotgun app)
1. Choose a project which has been assigned to the configuration
1. Click the **Arrow** in the top right and choose the **new configuration**

-------------------------------------------------------------------------
