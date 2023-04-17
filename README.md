# Ionic-App-Projects-2023
Build Ionic Apps Using latest technology



1.Build Your First Ionic App: Photo Gallery (Ionic Angular and Capacitor)
    How to Run
    Note: It's highly recommended to follow along with the tutorial guide, which goes into more depth, but this is the fastest way to run the app.

    Install Ionic if needed: npm install -g @ionic/cli.
    Clone this repository.
    In a terminal, change directory into the repo: cd photo-gallery-capacitor-ng.
    Install all packages: npm install.
    Run on the web: ionic serve.
    Run on iOS or Android: See here.

    -npm install -g @ionic/cli native-run cordova-res
    -ionic start photo-gallery tabs --type=angular --capacitor
    -cd photo-gallery
    -npm install @capacitor/camera @capacitor/preferences @capacitor/filesystem
    -npm install @ionic/pwa-elements

    Next, import @ionic/pwa-elements by editing src/main.ts.

    import { defineCustomElements } from '@ionic/pwa-elements/loader';

    // Call the element loader after the platform has been bootstrapped
    defineCustomElements(window);

    -ionic serve
