Sample Vuetify Theme

Upon converting to a Nuxt compliant format , the following needs to be noted:
- App.vue -> layouts ->Default
- Home.vue(/ route) -> Pages -> index.vue.
- Conditions which use the namespace Home needs to be changed to index.
- All hardcoded routes in the code needs to map the exact page name.
- images which were previously accessed using /static/*.img  needs to be modified to remove the /static/ prefix.

