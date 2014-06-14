# Sublime DoubleClick Boilerplate

A Sublime Text 2/3 snippet to generate the HTML5 Boilerplate (v4.3.0) template.

## Install

### Option 1: Manual

Copy the files to your Packages directory.

### Option 2: Package Control

In the command pallette (Cmd-Shift+P on Mac) type 'Install' then press enter to see a list of packages. Search for 'HTML Boilerplate' then press enter to install.

## Usage

With a blank HTML file open, type

    dcboiler

and press `TAB`.

That generates:

    <!DOCTYPE html>
    <html>
      <head>
        <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <script type="text/javascript" src="http://s0.2mdn.net/ads/studio/Enabler.js"></script>
        <!-- build:css({.tmp,src}) main.css -->
        <link rel="stylesheet" href="main.css" type="text/css">
        <!-- endbuild -->
        <!-- build:js({.tmp,src}) main.js -->
        <script src="main.js" type="text/javascript"></script>
        <!-- endbuild -->
      </head>
      <body>
        <div id="container">
            <div id="content" class="hide">

                <!--BACKGROUND + LOGO
                <div class="background" id="background">
                    <div class="logo" id="logo"></div>
                </div>
                BACKGROUND + LOGO-->

                <!--FRAMEONE
                <div class="frameOne" id="frameOne">
                  <div class="frameOneText1" id="frameOneText1"></div>
                  <div class="frameOneText2" id="frameOneText2"></div>
                  <div class="frameOneImg1" id="frameOne1"></div>
                  <div class="frameOneImg2" id="frameOne2"></div>
                </div>
                FRAMEONE-->

                <!--ENDFRAME
                <div class="endFrame" id="endFrame">
                  <div class="endFrameText1" id="endFrameText1"></div>
                  <div class="endFrameText2" id="endFrameText2"></div>
                  <div class="endFrameImg1" id="endFrameImg1"></div>
                  <div class="endFrameImg2" id="endFrameImg2"></div>
                </div>
                ENDFRAME-->

            </div>
        </div>
      </body>
    </html>

## License 

[MIT Licensed](http://sloria.mit-license.org/).