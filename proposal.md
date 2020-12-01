# Create the VLC User Documentation for one Mobile Port(Android) Project Proposal

*Writer Name*: **Avii**

*Full Name*: **Avinal Kumar**

*Email*: **185067@nith.ac.in**

*Résumé/CV*: https://docs.google.com/document/d/1zZviZNtVPCAxoTQv2sHXYAF7DHYz3gbYtsrPkja2F9o/edit?usp=sharing

*Additional information*: I have been writing documentation for my own projects for 2 years now. Other than that I have been actively contributing on Quora and Stack Overflow. VLC for android is a great application and packs a lot of features. But there is no proper documentation to cover them all. I would like to write a relevant and easily readable documentation that could help the people to explore the full potential of the app.

## ABSTRACT
User documentation is used as a static support system to assist end-users. It provides both technical and non-technical information about a product or service. It helps users 
learn how to use software or service. Not every person wants to contact support or wait for an email reply if all he needs is a little direction, tips, or trick. User 
documentation just does that. It also reduces support costs and is an identity of the product’s healthiness and the developer team.

VLC for Android has been downloaded over 100 million times from Google play store alone. VLC provides lots of features for its mobile ports ranging from audio-video playback 
to network stream. Often people want to use these awesome features but they are unable to do so. Searching for a blog or some random video for this requires a lot of time 
and patience and still, there is no authenticity of the information obtained. Currently, VLC hosts VLC for Android user documentation on the wiki page and provides less or 
no description of these features. In addition to that, wiki pages were last updated in March 2019. The current project will provide new User documentation with a modern 
design and greater ease of use for the Android port.

## CURRENT SITUATION
The wiki pages are completely outdated and contain very less information about the latest version of VLC. Also, they are not easy to navigate. There is no visible option to 
read the documentation in another language than English. It doesn’t contain feature descriptions at all.

ANALYSIS
* As of now the current documentation is obsolete and needs to be written in a new way and using a different platform and tools.

* Most android users have little or no technical knowledge. But there are people who need more technical information about a feature. Writing and maintaining two separate 
documentation for each of the above purposes is not a good idea. Or even in the same documentation dividing a feature based on technical and non-technical creates additional 
confusion. Because again most of the user are used to the UI they see or the features they use, this is not easy for everyone to decide if something is technical or non-technical. So we would want to simplify this for them.

* Most of the users will try to get information through their smartphone itself and rest through desktop or other devices. So the documentation should be easily adaptable to 
every screen size. And shall create no confusion about navigation.

* Not every feature of the desktop version is available in android port and if available doesn’t work the same in both ports. This is because desktop application have been 
in development for much longer and it has achieved a kind of saturation state, in contrast mobile port is relatively new and still developing. Other than that, although 
now-a-days mobile devices are becoming so powerful, there is obvious restriction on type of feature we can incorporate mostly due to demand of the end user. Having a feature 
no one uses is waste of development resources. So Conversing both documentation on the basis of features is not recommended.

## BASED ON ABOVE ANALYSIS I PROPOSE THE FOLLOWING.
1. As of now Desktop user documentation is using the Sphinx Documentation generator and Read the Docs theme. Using the same for the Android port will help us in the following 
ways:
  * Easy merging of both the documentation.
  * It is optimized for all screen sizes.
  * Seamless experience when navigating to Android User Documentation through Desktop Documentation

2. Separating the chapters, sections and subsections according to their relative position in application. For example - Background/PiP mode is inside More -> Settings->Video, 
So the chapter structure will be
  ```
    More
    |__Settings
    | |__Media Library
    | |__Video -->Background/PiP Mode
    : :
  ```
  * This approach will improve ease of access since users will be able to navigate to the part easily where they need help by comparing it to the relative location in the 
  application. For each of the features we can further separate technical and non technical parts. We shall first write a non-technical easy description and then further 
  highlight or label technical parts of the same feature, if any, just below it. This might lead to some repetition but it will ensure smooth experience of non-technical 
  majority. This will also help in future by future by increasing maintainability. As the application will reach saturation state the relative UI is not likely to change 
  much, so in future if a new feature is added/removed we can simply refactor the section. In case the whole UI is changed, we can rearrange the sections/chapters or 
  restructure the whole doc, either case we need to modify the whole documentation because screenshot shall have to be replaced to match current UI.

3. Each section of the documentation shall consist of a labelled screenshot , description of the feature, more technical part if any and tips and tricks for the feature.

  * Independently developing this user documentation from the desktop will help us merge both documentation in only a few steps without affecting the current documentation 
  or being affected by it during development. I propose to place this whole documentation in the Android section of the desktop documentation once it is developed and then 
  creating a permalink for the VLC for android documentation.

  * More improvements may include redesigning the start page of the Desktop user documentation to let users directly choose their favorite OS and then redirecting to the 
  chosen OS’s documentation. Since Windows, MacOS and Linux VLC user documentation is already well designed and conversed we may put options to choose from 
  Windows/MacOS/Linux or Android or iOS. This will result in nicely separated but unified user documentation with just one link to use for all ports.

## WHY IS MY PROPOSED USER DOCUMENTATION BETTER?
This proposed user documentation is structured on the basis of the common patterns followed by the end user to get help. The documentation combines all the required features 
e.g. Simplicity, Clarity, Look and feel, technological knowledge to maximize the ease of use and end user experience. This is also easily maintainable since there is no 
longer need to maintain individual user documentation for every port.

## WHY AM I RIGHT PERSON FOR THIS PROJECT?
* I have been writing codes for 2 years now and often I need to go through the API documentation for certain libraries or some software or even document my own code. So I 
know exactly what people want to see in the documentation, what problem they face and how they approach to get help. I shall be able to apply the same experience to write a 
consistent and easily readable documentation.

* I have been actively writing technical stuff on Quora, Stack Overflow and various other platforms. I know how to explain things in a way that is catchy and people easily 
understand.

* VLC for Android is a powerful and highly famous tool, yet most of its features are either unknown or there is no help available. I have been using VLC on both desktop and 
mobile platforms for many years now and I know what problems a user may face. Combing all my knowledge and experience I can assure a great documentation.
