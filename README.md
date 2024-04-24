# Responsive-Web-Design--Day_1

1. Provide a different CSS file for all the type of devices.

        <!-- Important This We Have to Remember -->

          Width & Height
          min-width,min-height
          max-width,max-width
          orientation - Portrait and Landscape

        <!-- learn About some Units (Different Devices) -->

            min-width,min-height & max-width,max-height

        <!-- In CSS, We Use @Media (it is called as Media Query)  for Example-->

            @ media type and( Apply the condition )

            & Type means -> all/screen/print

            @media screen(max-width:200px){
                    body{
                        background-color: blue;
                    }
            }

        this is a example.

        <!-- using All Type --> 

        example:

        @media all(oriented-Portrait){
                body{
                    background-color: yellow;
                }
        }

        <!-- using media in anchor tag without using @media Query in Css Styling -->

            <link href="mobile.css" media="screen and (max-width:320px)/>