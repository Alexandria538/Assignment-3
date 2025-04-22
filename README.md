# Assignment_03
Assignment 3 for Generative AI and Design, VIZA 626 at Texas A&amp;M University (Spring 2025)

<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->




<!-- PROJECT LOGO -->
<br />
<div align="center">
  </a>

  <h3 align="center">Assignment_3: Photoshop Batch Rendering Using Actions for Stylistic Video Editing</h3>

  <p align="center">
    My project is trying to explore the use of Photoshop's tools, specifically the Batch Render Processing System and the Actions Tool, to create an alternative pipeline for photo group and video editing by systematic automation of image manipulation. My primary goals were to establish consistent application of different style edits and evaluating the feasability of using Photoshop as an alternative video editing tool. 
    <br />
    <a href="https://github.com/Alexandria538/Assignment-2/blob/main/Assignment_2_Final.pdf"><strong>Link to PDF Report »</strong></a>
    <br />
    <br />
    <a href="https://tdelafuente.myportfolio.com/">Tessa DeLaFuente</a>
    &middot;
    <a href="https://sites.google.com/view/viza626/home">VIZA 626</a>
  </p>
</div>


[![Assignment-2][images-fig1]](https://example.com)
*Fig. 1. These are the nine style explorations I did based on my initial image on the top left, using Adobe Firefly’s Generations and editing in Photoshop. The styles are: Original, Oil Painting (Vincent Van Gogh), Art Nouveau (Alphonse Mucha), Cubism (Pablo Picasso), Fauvism (Andre Derain), Horror Movie (Steven King), Yarn (DreamWorks Trolls), Cut out Paper (Bill Braun), Comic Book (Marvel Comics), Watercolor (Children’s Book - Jerry Pinkney).* 

<!-- Abstract -->
## Abstract
My project looks at an efficient workflow for creative image/video editing using Adobe Photoshop Actions tool and Batch Processing System. This innovative approach to video editing through Photoshop creates a fundamental shift to creative workflow management through the integration of industry-leading image manipulation with video editing techniques. Through systematic automation of Actions, users can achieve a simple and consistent application of visual edits across a string of images. This approach provides an alternative method to optimize productivity while ensuring uniform results across image collections through a post-processing pipeline. 

**Additional Key Words and Phrases:** Adobe Photoshop, Adobe Premiere Pro, Automated Workflow, Batch Rendering, Creative Editing, Error Recovery, Frame-by-Frame Processing, Style Replication, Systematic Automation, Visual Consistency, Time Optimizaiton. 

<!-- Introduction and Related Works -->
## Introduction and Related Works
As a digital artist passionate about video/creative editing with movies like Wolf Walkers, The Mitchells vs The Machines and Loving Vincent as inspiration, I've found Adobe Photoshop to be an invaluable tool for both video and image manipulation *[Figure 2].* While traditionally known as an image editing tool, using “...Batch to apply Photoshop actions to batches of images” offers powerful advantages for video editing workflows (Eismann, pg. 16). An action, defined as “a small file of recorded instructions…[which] can be 'played' on images,” can be saved and easily replicated by an artist, enabling consistent, highly customizable, time-efficient processing of multiple video frames while maintaining style and artistic integrity (Nichols, pg. 26). Photoshop is geared towards “photographers of all skill levels,” and thus, some may find it more comfortable to dabble in creative video editing (Nichols, pg. Xiii). While “there is more advanced video editing software such as Adobe Premiere Pro and Apple’s Final Cut…this software contains more features and is more complex”, and I experimented with this process because I think Photoshop has merit to be considered as effective video editing tool and may be used in conjunction with such programs to help workflows at least in rapid prototyping or if users are unfamiliar with certain programs (David, pg. 23).

## Methodology
My method for testing the capabilities of Photoshop for creating video or group image editing relied on two primary Photoshop features: the Actions Tool and the Batch Render Tool. Starting with royalty-free videos (or alternatively shot footage), I selected four slow-motion clips so that the motion wouldn’t be too distracting from the style alterations. I tried to make sure there was a clear focus and showed decent contrast and clarity to be visually interesting. *[Figure three]*. Each video was imported into Photoshop and transformed into a sufficient number of frames for smooth transitions *[Figure four]*. After saving the files, I created four creative styles to apply using tools like Filter Gallery, Stylize, Camera Raw filter, and Adjustment Layers. Documenting each step was crucial in order to efficiently replicate the process in an action recording. To do this, open a keyframe, go to the Action Panel>Create New Action in the Actions pane, and repeat the effects you wish to use *[Figures 5-8]*. Importantly, the save step must be included in the action recording. The Batch tool (File>Automate>Batch) was then used to apply these actions across folders, processing each file in two to ten seconds, depending on complexity *[Figure 9]*. Finally, I imported the processed sequences into Premiere Pro, handling possible naming sequence reversals by organizing images within bins before adding them to sequences and rendering them out. The resulting renders show distinctive style alterations but still retain the elements and movement fromt the original videos *[Figure 10]*. To demonstrate versatility, I applied multiple styles to different videos *[Figure 11]*, showcasing both customization options and action reusability across various clips.  

[![Assignment-2][images-fig2]](https://example.com)
*Fig. 2. This is a drawn-out pipeline demonstrating my creative process for this assignment. Starting with a clear original drawing, I pair it with whichever style exploration(s) I collect references to use to influence the generations. In Adobe Firefly, I use compositional and stylistic references on top of prompt input and filters. From this, I generate any number of images, some of which will be unusable. Of the usable generations, I select 1 or multiple to bring into the editing phase in Photoshop. Here is where kit bashing, touch-ups, cropping, color correction, filters, and other editing techniques occur. Depending on the style, this part can be more or less intensive but the result should be compositionally similar to the original drawing but should demonstrate the elements of the target style.*
[![Assignment-2][images-fig3]](https://example.com)
*Fig. 3. Here are examples of stylistic matching within my project. I have selected four of my nine images and compared them to my references which I use as stylistic references in Adobe Firefly.*
[![Assignment-2][images-fig4]](https://example.com)
*Fig. 4. This is a range of generations I did for the Yarn style influenced by the screen captures of the DreamWorks movie Trilogy Trolls. While the images largely look similar, there are small differences that persist in color, texture, lighting, etc. For this, I decided to generate no less than 20 images for each style. The more I generated and experimented, the closer I was able to lead Firefly to generate images more to my target style.*
[![Assignment-2][images-fig5]](https://example.com)
*Fig. 5. Here we see the process of editing, specifically for the Comic Book style image. From the compositional and style references, which I decided to experiment with two different comic covers from Marvel, I selected a main generation to serve as a base for my final and a secondary generation to serve as a kit bash doner. After upscaling the images in Firefly to produce higher quality images, the first step in Photoshop was to extend the crop of the image to include all of the hat. I also pulled the lower legs and feet from the doner generation. After correcting colors to better fit my original drawing, I decided to do more, and kit bash the front of the Scarecrow’s torso because the simpler style I found translated more to a comic style. After a few touch-ups, I decided that this image reached a good balance between the references.*
## Result and Future Work
With the videos I created, I believe I have shown that maintaining consistency and showing a lot of customizability were easily attainable through the use of these Photoshop tools. The process also shows flexibility between file types and easier recovery from errors as the process can be easily replicated or altered based on artistic need. Depending on the effects used, the consistency between frames may be affected by Jittering. I found there are methods to cut down on flickering via tools like deflicker in Premiere Pro (Pueringer). It did arguably take a longer time than video processing programs, but I had already expected that, and I was nonetheless happy with the outcomes of the stylizing. The process of highlighting the usefulness of batch rendering and action recording for video editing, rather than photo grouping alone, I believe, was a success. I would like to explore other tools to add in conjunction with the action tool or other programs that can benefit from the process of quick image stylization. For example, EbSynth, which requires selected keyframes, would benefit from this by selecting the specific files you wish to use and putting them through a relatively small batch render to cut down on time (Secret Weapons). 

[![Assignment-2][images-fig6]](https://example.com)
*Fig. 6. Here are examples of some of the unusable renders brought on by Firefly hallucinations. The majority of such hallucinations I found come from the upscale process, where the software messes up and delivers an entirely new image rather than a better-quality version of the selected image. White these are not my intended product, due to diverting more from the compositional reference, this did allow me to look at the elements of the styles in a new way and helped me fine-tune my settings to achieve generations more akin to my target style.*

[![Assignment-2][images-fig7]](https://example.com)
*Fig. 7. Of my nine generations of various styles, I found some consistency in the results. The 3-D styles [Blue: Horror Movie (Steven King), Yarn (DreamWorks Trolls), Cut out Paper (Bill Braun)] were the ones that generally required the least amount of editing outside of color correction or simile kit bashing. The general 2D styles [Green: Oil Painting (Vincent Van Gogh), Art Nouveau (Alphonse Mucha), Comic Book (Marvel Comics), Watercolor (Children’s Book - Jerry Pinkney)] required more editing to achieve their styles, whether it involved touch-ups, color correction, outlining, or more involved kit bashing. The abstract styles [Red: Cubism (Pablo Picasso), Fauvism (Andre Derain)] required the most in the editing phase. This shows that some styles are more easily replicable in Firefly, but there are methods in the editing phase that can combat this by building upon the generations.*

## Conclusion
Through this project, I discovered that Photoshop’s Actions and Batch Processing tools offer a uniquely distinctive entry point into image and video editing, valuable for photographers or armature digital artists. While traditional video editors like Premiere Pro excel at timeline-based editing, Photoshop’s frame-by-frame approach provides good control over visual aesthetics. The most memorable aspect was witnessing how you could transform dozens of frames quickly, demonstrating the power of systematic automation in creative workflows. This reinforced that efficiency and creativity aren't mutually exclusive – with the right tools and methodology, artists can maintain high-quality standards while significantly reducing processing time.

<!-- Bibliography -->
## Bibliography
[1] Eismann, Katrin, and Wayne Palmer. Photoshop restoration & retouching. Peachpit Press, 2006.

[2] Geller, Marty. “ Photoshop: How to Create the Look of Watercolor Paintings.” YouTube, Blue Lightning TV, 17 Apr. 2022, www.youtube.com/watch?v=FhgTFAUZrMs.

[3] Horowitz, David. "Teaching video editing and motion graphics with Photoshop." Innovative Marketing 13.3 (2017): 17-24.

[4] Nichols, Robin. Mastering Adobe Photoshop Elements 2022: Boost your image-editing skills using the latest Adobe Photoshop Elements tools and techniques. Packt Publishing Ltd, 2021.

[5] Powell, Noel. “Watercolor Painting Effect Tutorial - After Effects.” YouTube, Creation Effects, 11 May 2016, www.youtube.com/watch?v=tix2u3Hg9lA. 

[6] Pueringer, Niko, and Dean Hughes. “Did We Just Change Animation Forever?” YouTube, Corridor Crew, 26 Feb. 2023, www.youtube.com/watch?v=_9LX9HSQkWo.

[7] Xu, Chengyuan. “Coherent Video Style Transfer Demo (2019, Private).” YouTube, YouTube, 27 Oct. 2022, www.youtube.com/watch?v=nQ_itjCBEAs.

[8] “About Actions and the Actions Panel.” Actions and the Actions Panel in Photoshop, 25 Sept. 2023, helpx.adobe.com/photoshop/using/actions-actions-panel.html. 

[9] “EbSynth - Tutorial.” YouTube, Secret Weapons, 3 July 2019, www.youtube.com/watch?v=0RLtHuu5jV4.

[10] “Make Any Photo Vintage in Adobe Photoshop | Tutorial.” YouTube, SonduckCreative, 20 Jan. 2023, www.youtube.com/watch?v=Oa5qvjTkCuY.  

[11] “Process a Batch of Files.” Process a Batch of Photoshop Files, 24 May 2023, helpx.adobe.com/photoshop/using/processing-batch-files.html. 

<!-- CONTACT -->
## Contact

Email - alexandria538@tamu.edu

Personal Website: (https://tdelafuente.myportfolio.com/)




<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

This work is submitted as part of Assignment 3 for the VIZA 626 course at Texas A&M University, under the instruction of Professor You-Jin Kim, during the Spring 2025 semester.

VIZA 626 Class Website: [https://sites.google.com/view/viza626/](https://sites.google.com/view/viza626/home)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[images-fig1]: fig1.png
[images-fig2]: fig2.png
[images-fig3]: fig3.png
[images-fig4]: fig4.png
[images-fig5]: fig5.png
[images-fig6]: fig6.png
[images-fig7]: fig7.png
[images-fig5]: images/fig5.png
[images-fig6]: images/fig6.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com
