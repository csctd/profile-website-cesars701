# Profile Website

Welcome to my profile webiste, girlie pops <3 
<!-- enter your target audience after the comma above -->

This template is designed for use in the URI CS TD SSP. 


## Tips for Updating the Content of this site

- sidebar variables are defined in `info-.yml` 
- sidebar formatting for sidebar is in `_templates/hello.html` 
- variables are used via `html_context`
- get social links back by removing setting to `navbar_end` in `conf.py` and set values by [example](https://github.com/choldgraf/choldgraf.github.io/blob/main/conf.py#L41)


## To work with this repo offline (or in codespaces)

**This requires having python installed then installs a package that helps build the website**

The easiest way to build the website is to use `nox`, which handles all of the environment generation automatically.
To do so, follow these steps:

1. Install `nox`.

   ```shell
   pip install -U nox
   ```
2. To run a live webserver that will auto-build and reload when you make changes, run:

```shell
nox -s docs-live
```

If on Codespaces, use accept the port forwarding and open the forwarded port in a new browser tab to preview your site while you work. 

<!-- 
Run `nox`
   ```shell
   nox -s docs
   ```
this should install a Sphinx environment and build the site, putting the output files in `_build/html`. -->

Since you're here, you might be: 
- Gina, I know you love video games! Gina loves video games, so Gina checks my website to see the latest video game info.
- Tim, we're apart of the same community. Tim is a part of the LGBTQ+ community, he loves having a safe space.
- Elizabeth, your my best friend! Elizabeth just wants to check out my website and the work I have done because she's my best friend.
<!-- make a bulleted list of 3 fictional visitors to your site. Include a few detials about them that could impact how you design for them. For each visitor, assign a task or goal they have for visiting your profile website -->

## Design
I will be using visual heirarchy a lot in my website design. Using images for album covers, video game art, etc. to draw the user's attention to that. I also will use cute pastel colors that will appeal to the audience that I want to bring this to. Moving images will be very important to my website design, so I will use them where I see fit and to where I want it to fit the aesthetic. 

## Accessability
I want to make sure that the fonts and font colors are readable enough for users who may have visual impairments such as color blindess, or blindness in general. Using bigger fonts, but also allowing for the user to adjust the fonts and colors themselves if possible. If I link any video clips, I want to make sure they have closed captioning for the users who are hard of hearing. I will test using my keyboard only to see if users are able to access content that has to be clicked, etc. I could also test how my website looks like with each different type of color blindness to make sure it looks well for the user.
