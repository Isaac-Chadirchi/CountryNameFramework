# CountryNameFramework
Modders resource for country names in the video game "Hearts of Iron 4"
Steam workshop link: TBA

The default localisation files that are used for country names in HoI4 are an outright mess. No comments, no real order or sense to it. It is an absolute ball ache to work with (and whoever wrote it should be ashamed, and needs to do better).
The aim of this project is to rewrite these files, to make them somewhat reasonable to work with when making country name edit mods. Only planned to support english at this time.

The main changes to be implemented by this mod include:
Spliting the main country localisation into several different files, to impove readablity
Making nation entries formatted in a reasonable way
Adding code comments where relevant
Grammar fixes, and addition of some missing definitions
Removal of the PDX internal versioning system for individual definitions - I feel it is wholly unnecessary

Detailed explanation:
This framework utilises the "replace" feature to update the different country definitions. This should allow for the framework to continue to work despite PDX updates. Within the replace folder, definitions are split between different countries and cosmetic files, based of major status, geographic region, releasables, etc. countries files will contain generic definitions, whilst cosmetic will contain more specific definitions.

Licensing shit:
You're free to use this framework for the creation of your own mods. Any free mod which utilises this framework in it's creation must credit the original author. Any paid mod must first contact the original author to discuss terms before this framework can be used.
You're not allowed to reupload this framework to github or the steam workshop, and any reuploads in other places should make clear it is not an official upload, and credit the original author. You're not allowed to reupload this framework for commercial purposes.
The original author reserves all rights to deny use of this framework to any party, for any reason.
