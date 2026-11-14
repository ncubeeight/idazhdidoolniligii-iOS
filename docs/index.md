---
layout: default
---

i’dazhdi’doolniłígíí is a version of [Déjà Entendu](https://github.com/ncubeeight/deja-entendu), an iPhone app for language learners, with an open-source Diné bizaad (Navajo) dictionary added. It looks up meanings and reads aloud about 11,000 Navajo words, all on the device, with no account and no cloud service.

## Yours to clone, fork and build on

This app is meant to be carried forward by developers from the Navajo Nation. You're free to clone it, fork it, rename it, rebrand it, change it and publish your own app from it. What you build from it is yours.

The app's code is under the [Apache License 2.0](https://github.com/ncubeeight/idazhdidoolniligii-iOS/blob/main/LICENSE). It lets you use, change and distribute it, including in paid or commercial apps, under whatever terms you choose for your own work. The license only asks you to keep its copy and the existing copyright and credit notices with the code.

The Navajo dictionary data has its own license; see [Acknowledgements](#acknowledgements) below.

## Get started

You'll need a Mac with Xcode 26 or later. The app runs on iOS 26 or later.

1. Fork [ncubeeight/idazhdidoolniligii-iOS](https://github.com/ncubeeight/idazhdidoolniligii-iOS) on GitHub, or clone it directly:

   ```
   git clone https://github.com/ncubeeight/idazhdidoolniligii-iOS.git
   ```

2. Open `Déjà Entendu.xcodeproj` in Xcode.
3. Under **Signing & Capabilities**, choose your own team and change the bundle IDs (`com.ncubeeight.dejaentendu` and `com.ncubeeight.dejaentendu.share`) and the App Group to your own.
4. Build and run on your iPhone or the Simulator.

## About the Samples menu

> Please consider that the application has a capability to generate text samples for some languages. This is based on a capability that is bundled with iPhones referred to as a "foundation model" or "large language model". There are a large number of older phones that do not have this LLM and therefore cannot generate example sentences or paragraphs in the Samples menu. Because Apple does not yet have a custom LLM for the Diné language, dynamic samples cannot yet be constructed for selected terms in the Samples menu. So static definitions from the Diné Bizaad dictionary are used. Future developers may wish to update or alter the Diné dictionary in future versions. Apple may also offer support for Diné Bizaad at a later date.

## Acknowledgements

The Diné bizaad word meanings and read-aloud come from [NavajoKit](https://gitlab.com/HullBreach/navajokit) by Daniel Gump, licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). The app builds it from the public fork [ncubeeight/navajokit-new](https://github.com/ncubeeight/navajokit-new) under the same license. If your app includes this dictionary, keep this credit. If you change and share the dictionary itself, share those changes under CC BY-SA 4.0 too. This applies only to the dictionary, not to the rest of your app.

Thank you, Daniel, for making Navajo language tools freely available.
