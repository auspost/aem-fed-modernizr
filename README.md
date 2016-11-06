# AusPost AEM - Modernizr

This repository is used as CDN for a custom version of Modernizr during development process.

the AEM Front-end build production task creates a custom version of Modernizr including only the required feature. That custom version is loaded in production. However, to avoid complexity and to save time during development process, that custom version is not part of the default task. For more information, please refer to private AEM Front-end repo.

Features Excluded:
- Hidden attribute: conflict with auspost styleguide
- Notification: conflict with AEM notification component
