FaceFusion
==========

> Industry leading face manipulation platform.

[![Build Status](https://img.shields.io/github/actions/workflow/status/facefusion/facefusion/ci.yml.svg?branch=master)](https://github.com/facefusion/facefusion/actions?query=workflow:ci)
[![Coverage Status](https://img.shields.io/coveralls/facefusion/facefusion.svg)](https://coveralls.io/r/facefusion/facefusion)
![License](https://img.shields.io/badge/license-MIT-green)


Preview
-------

![Preview](https://raw.githubusercontent.com/facefusion/facefusion/master/.github/preview.png?sanitize=true)


Installation
------------

Be aware, the [installation](https://docs.facefusion.io/installation) needs technical skills and is not recommended for beginners. In case you are not comfortable using a terminal, our [Windows Installer](http://windows-installer.facefusion.io) and [macOS Installer](http://macos-installer.facefusion.io) get you started.


Usage
-----

Run the command:

```
python facefusion.py [commands] [options]

options:
  -h, --help                                      show this help message and exit
  -v, --version                                   show program's version number and exit

commands:
    run                                           run the program
    headless-run                                  run the program in headless mode
    batch-run                                     run the program in batch mode
    force-download                                force automate downloads and exit
    job-list                                      list jobs by status
    job-create                                    create a drafted job
    job-submit                                    submit a drafted job to become a queued job
    job-submit-all                                submit all drafted jobs to become a queued jobs
    job-delete                                    delete a drafted, queued, failed or completed job
    job-delete-all                                delete all drafted, queued, failed and completed jobs
    job-add-step                                  add a step to a drafted job
    job-remix-step                                remix a previous step from a drafted job
    job-insert-step                               insert a step to a drafted job
    job-remove-step                               remove a step from a drafted job
    job-run                                       run a queued job
    job-run-all                                   run all queued jobs
    job-retry                                     retry a failed job
    job-retry-all                                 retry all failed jobs
```


Documentation
-------------

Read the [documentation](https://docs.facefusion.io) for a deep dive.
Dear facefusion Team,
Hope this email finds you well. I'm Jack chan, hailing from China. Your facefusion project has become extremely popular in the short - video domain in China. Many of my friends and I have been actively using it, and we've created numerous fascinating videos with it. We are truly grateful for the efforts your team has put into this project. It's undoubtedly a great invention in the AI field and has opened up new creative possibilities for us.
I can't express enough how much I appreciate the remarkable work you and your team have done. Your decision to open - source facefusion has truly been a game - changer, enabling countless individuals, including myself, to explore the fascinating world of face - swapping technology.
I've been using facefusion in various scenarios, especially in my personal video - editing projects and some small - scale digital art experiments. The basic functionality of facefusion is already quite impressive, but during my usage, I've encountered a few issues that I believe could potentially be improved, and I hope you don't mind me sharing my thoughts with you.
First, the problem of face flickering during video face - swapping is quite common. For example, when I was creating a short video montage with face - swapped scenes, every time the camera angle changed slightly, the face on the screen would flicker, which was really distracting. This not only disrupts the smoothness of the video but also reduces the overall quality of the face - swapping effect. It would be amazing if there could be a way to address this issue, perhaps by optimizing the face - tracking algorithms or the image - blending techniques.
Second, when using the Second, when using the inswapper_128 model, which is supposed to be suitable for Asian faces, I noticed that the expressions of the swapped faces often look rather dull. In many real - life situations, people have a wide range of expressions, like pouting, closing eyes, or sticking out their tongues. But with the current model, these expressions are not well - replicated. I recently came across the live - portrait project, which seems to have some advanced techniques for expression handling. I'm not sure if it's feasible, but perhaps some ideas or technologies from live - portrait could be integrated into the inswapper_128 model to enhance its expression - handling capabilities. This would make the face - swapping scenarios more diverse and the resulting faces more vivid and natural. model, which is supposed to be suitable for Asian faces, I noticed that the expressions of the swapped faces often look rather dull. In many real - life situations, people have a wide range of expressions, like pouting, closing eyes, or sticking out their tongues. But with the current model, these expressions are not well - replicated. I recently came across the live - portrait project, which seems to have some advanced techniques for expression handling. I'm not sure if it's feasible, but perhaps some ideas or technologies from live - portrait could be integrated into the inswapper_128 model to enhance its expression - handling capabilities. This would make the face - swapping scenarios more diverse and the resulting faces more vivid and natural.
Third, regarding the real - time face - swapping feature, I've tested it on several mid - range graphics cards, such as the NVIDIA GeForce GTX 1660S, RTX 2060, and even the RTX 3060. On all of these cards, there is a significant delay during real - time face - swapping. For instance, when I tried to use facefusion for a live - streaming face - swap experiment, the delay was so long that it made the interaction very awkward. Given the popularity of these mid - range graphics cards in the consumer market, improving the real - time performance on such hardware would greatly enhance the user experience. Maybe there are some optimizations in the code execution or parallel processing that could be explored.
I truly understand that developing a project of this magnitude requires an enormous amount of time, effort, and expertise. I apologize in advance if my suggestions seem presumptuous or if they have overlooked some technical complexities. I'm just a passionate user who wants to see facefusion become even better.
Thank you again for your incredible contribution to the field. I sincerely hope you'll consider my suggestions. Whether you decide to optimize based on them or not, I'd be extremely grateful if you could get back to me. Please feel free to reach out to me at cyajyywn@qq.com. I'm looking forward to your reply.
Best regards,
Jack chan
January 24, 2025


