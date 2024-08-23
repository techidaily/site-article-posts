---
title: "[Updated] A Beginner's Tutorial on Using LUTs in AR"
date: 2024-08-22T15:52:38.382Z
updated: 2024-08-23T15:52:38.382Z
tags: 
  - screen-recording
  - ai video
  - ai audio
  - ai auto
categories: 
  - ai
  - screen
description: "This Article Describes [Updated] A Beginner's Tutorial on Using LUTs in AR"
excerpt: "This Article Describes [Updated] A Beginner's Tutorial on Using LUTs in AR"
keywords: "AR LUT Basics,Beginners Guide to LUTs,Using LUTs in AR,LUTs for AR Devices,Introduction to AR LUTs,Learning AR LUT Techniques,Essential AR LUT Tutorial"
thumbnail: https://thmb.techidaily.com/f17f33138f47cc809c1c7740ec4a954bd7d355028092c16b39a2af30bc8bac07.jpg
---

## A Beginner's Tutorial on Using LUTs in AR

Color LUTs (Lookup Textures) are tables of RGB color values. In Spark AR, you can use color LUTs to quickly create color gradation effects throughout the scene. Go through the article and create your color LUT effect.

## Part 1\. What are Luts in Spark AR used for?

To create a color filter effect in [Spark AR](https://sparkar.facebook.com/ar-studio/), you need a color LUT in Spark AR.

To develop AR effects for mobile cameras, you can use the Mac and Windows augmented reality platform Spark AR Studio. Imagine it like Sketch or Photoshop for augmented reality. The color values of the camera texture are mapped to the x, y, and z coordinates of the location in the color LUT. This location contains a corresponding output color that is drawn over the scene to create a color gradient effect.

![create a color gradient effect](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-1.jpg)

## Part 2\. How to use LUTs in Spark AR?

**How to apply a color LUT to the whole scene in Spark AR:**

##### Step1Add a color LUT to your project

1. In the Assets panel, click Add Asset.
2. Select Import, then Color LUT, and select your file from your computer.

When you import a color LUT, compression is always set to None, and filtering is set to Low by default.

##### Step2Apply to the whole scene

1. In the Assets panel, right-click the LUT color.
2. Select Actions and then **Apply to Camera**.

A patch graph is automatically set that applies a color LUT to the entire scene.

![apply to the whole scene](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-2.jpg)

**The color LUT patch graph**

The patch graph that renders the color gradation effect looks like this:

![color lut patch graph](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-3.jpg)

**To create the effect:**

* Fix Scene Render Pass renders cameraTexture0 and all objects in the scene that are children of the device. This creates the output texture.
* ColorLUTShader looks up the RGBA values of this texture in the Tension color LUT array and converts them to a new green color. This will change the texture and create a gradient effect.
* Finally, the Screen Output patch renders the green color.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
## Part 3\. Free LUTs resource for Spark AR

Here are the best free LUTs resources for Spark AR:

### 1\. [Frost Zombie (Technical Showcase)](https://we.tl/t-1uj4wJKluG)

Client filter pieces occasionally end up on the scrap heap. It was a poor Frost Zombie in this instance. Since this is one of my simpler filters, I felt it was okay to publish the build information. Four objects make up much of the scene: an EyeColor block, a custom canvas segmentation, a face mesh, and an emitter for the breath mist (my personal favorite). To show the layers used in generating the primary zombie texture, I also moved to Substance Painter. This is a demonstration of my methods rather than a step-by-step manual.

![frost zombie](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-4.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 2\. Fur

Here are the key building principles.

* Geometric layers, often known as shells, produce depth.
* Normals is used to create shells from a single mesh.
* Alpha decreases with each shell.
* Deeper shells are darker.
* Height is generated from a single grayscale channel.
* No fur is generated in the black areas of the height texture.

![fur](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-5.jpg)

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
### 3\. Shockwave

Even while using large image sequences is frequently discouraged, you can still use them to make some extremely spectacular effects! I'll explain how the screen tap computation procedure relates to texture position in this walkthrough. If you want to apply this approach and texture sequence in your projects or give it a try.

![shockwave](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-6.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
### 4\. Transition Curves

There are 11 distinct animation curves included with Spark AR in the Transition patch. Here is a helpful visual aid because it might be challenging to distinguish between a quartic and a quintic when working on a project. With the SDF circle doubled (to sharpen the edge) and inserted into the Patch Pack's alpha channel, the circles are likewise straightforward rectangles. Since RGB values are three times one, the object is white.

![transition curves](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-7.jpg)

### 5\. Realistic Smoke

By adding smoke to a scene, you can easily add a lot of detail and realism. Nothing revolutionary is happening here. The particle emitter creates flat planes of smoke texture that are forced upward. The force slowly shifts left and right as seen in the patch editor. The Fade particle script (created by Josh Beckwith) enlarges the particles and fades them out at the same time.

![realistic smoke](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-8.jpg)

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
### 6\. Rainbow Glitter

Given how beautifully Glitter Rain was received, I believed it would be fitting to broaden the potential with an HDR setting. While Glitter Rain made use of two different colors, this technique makes use of an entirely colorless substance and gets its color information via HDR.

![rainbow glitter](https://images.wondershare.com/filmora/article-images/2022/08/how-to-use-luts-in-spark-ar-9.jpg)

<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Closing Thoughts

Spark AR is an amazing website for LUTs and color grading. Whether you're a new student or a seasoned pro, Spark AR Studio has all the features and capabilities you need to become a good video editor. You can download free LUTs from Spark AR and apply them to your videos. The article guides on how to use LUTs in Spark AR and how to download free LUTs. So, Spark AR is one of the best online websites for LUTs I have tried.

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/)For Win 7 or later(64-bit)

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/)For macOS 10.14 or later

[Free Download](https://tools.techidaily.com/wondershare/filmora/download/)For macOS 10.14 or later

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-posts.techidaily.com/new-2024-approved-action-cam-showdown-which-holds-the-crown-gopro-or-yi/"><u>[New] 2024 Approved  Action Cam Showdown  Which Holds the Crown - GoPro or Yi?</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-2024-approved-the-ultimate-strategy-for-posting-srt-content-socially/"><u>[New] 2024 Approved  The Ultimate Strategy for Posting SRT Content Socially</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-live-tv-streaming-guide-the-best-ten-and-their-comparison-for-2024/"><u>[New] Live TV Streaming Guide  The Best Ten and Their Comparison for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-mastering-the-microscopic-views-in-teams/"><u>[New] Mastering the Microscopic Views in Teams</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-mobile-filming-tools-for-tourists-for-2024/"><u>[New] Mobile Filming Tools for Tourists for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-the-essential-blueprint-for-exceptional-video-tutorial-creation/"><u>[New] The Essential Blueprint for Exceptional Video Tutorial Creation</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-top-vr-bike-games-a-compreayers-guide-for-2024/"><u>[New] TOP VR Bike Games  A Compreayer’s Guide for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-unveiling-nikons-1j5-a-4k-video-masterpiece/"><u>[New] Unveiling Nikon's 1J5  A 4K Video Masterpiece</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-2024-approved-emotive-expression-through-pictures-and-music-fusion/"><u>[Updated] 2024 Approved  Emotive Expression Through Pictures & Music Fusion</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-2024-approved-prime-picks-best-photo-displayers/"><u>[Updated] 2024 Approved  Prime Picks  Best Photo Displayers</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-astrological-flair-crafting-bios-for-each-zodiac-house-for-2024/"><u>[Updated] Astrological Flair  Crafting Bios for Each Zodiac House for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-creating-seamless-cartoons-in-windows-movie-maker-for-2024/"><u>[Updated] Creating Seamless Cartoons in Windows Movie Maker for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-curating-background-beats-for-video-releases-for-2024/"><u>[Updated] Curating Background Beats for Video Releases for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-in-2024-unveiling-gestures-in-tech-landscape/"><u>[Updated] In 2024, Unveiling Gestures in Tech Landscape</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-mastering-ps4-captures-with-obs-studio-your-complete-guide-for-2024/"><u>[Updated] Mastering PS4 Captures with OBS Studio - Your Complete Guide for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-ultimate-guide-to-ios-photography-apps-x-8/"><u>[Updated] Ultimate Guide to iOS Photography Apps (X, 8)</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-ultimate-home-theatre-devices-top-10-list-24-for-2024/"><u>[Updated] Ultimate Home Theatre Devices - Top 10 List '24 for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/disabling-automated-podcast-recommendations-on-spotify/"><u>Disabling Automated Podcast Recommendations on Spotify</u></a></li>
<li><a href="https://article-posts.techidaily.com/elite-mobile-filming-tech-for-iphones-for-2024/"><u>Elite Mobile Filming Tech for iPhones for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/from-idea-to-indulgence-exploring-the-world-of-diy-chocolate-designs-with-the-cocoa-press-printer/"><u>From Idea to Indulgence: Exploring the World of DIY Chocolate Designs with the Cocoa Press Printer</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-you-play-mp4-files-on-xiaomi-redmi-note-12t-pro-by-aiseesoft-video-converter-play-mp4-on-android/"><u>How do you play MP4 files on Xiaomi Redmi Note 12T Pro?</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-call-logs-from-oppo-a18-by-fonelab-android-recover-call-logs/"><u>How To  Restore Missing Call Logs from Oppo A18</u></a></li>
<li><a href="https://some-techniques.techidaily.com/imovie-why-does-it-alter-my-videos-for-2024/"><u>IMovie  Why Does It Alter My Videos for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-change-vivo-y100t-lock-screen-clock-in-seconds-by-drfone-android/"><u>In 2024, How To Change Vivo Y100t Lock Screen Clock in Seconds</u></a></li>
<li><a href="https://article-posts.techidaily.com/mastering-the-microscopic-views-in-teams-for-2024/"><u>Mastering the Microscopic Views in Teams for 2024</u></a></li>
<li><a href="https://buynow-info.techidaily.com/netgear-nighthawk-x4-wi-fi-extender-analysis-superior-coverage-and-connectivity/"><u>Netgear Nighthawk X4 Wi-Fi Extender Analysis: Superior Coverage and Connectivity</u></a></li>
<li><a href="https://article-posts.techidaily.com/personalized-branding-craft-your-logo-from-free-designs/"><u>Personalized Branding  Craft Your Logo From Free Designs</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-messages-back-from-lava-yuva-2-by-fonelab-android-recover-messages/"><u>Simple ways to get lost messages back from Lava Yuva 2</u></a></li>
<li><a href="https://article-posts.techidaily.com/the-art-of-color-transformation-an-expert-written-by-dr-jane-smith/"><u>The Art of Color Transformation  An Expert' Written by Dr. Jane Smith</u></a></li>
<li><a href="https://article-posts.techidaily.com/the-filmmakers-toolbox-in-depth-guide-to-cinematic-techniques-in-24-for-2024/"><u>The Filmmaker’s Toolbox  In-Depth Guide to Cinematic Techniques in '24 for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tutorial-implementing-microsoft-copilot-in-your-windows-workspace/"><u>Tutorial: Implementing Microsoft Copilot in Your Windows Workspace</u></a></li>
<li><a href="https://some-tips.techidaily.com/ultimate-selection-of-omnidirectional-recording-devices-for-2024/"><u>Ultimate Selection of Omnidirectional Recording Devices for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlock-the-power-of-ai-5-key-techniques-for-writing-superior-chatgpt-queries/"><u>Unlock the Power of AI: 5 Key Techniques for Writing Superior ChatGPT Queries</u></a></li>
</ul></div>
