# R-Shiny(normal)

## Use the Shiny to create the web with R

1.You need to install the package of Shiny
```
install.packages("shiny")
```

2.Also need to install the package of rsconnect for shinyapps.io that use this website to make the shiny code of R in web to carry out.
```
install.packages("rsconnect")
```

3.You need to create the ui and server.

The ui code is what you want to input, you can check out this website to find out what you need and see the code how to write.
```
https://shiny.rstudio.com/gallery/widget-gallery.html
```

4.The server code sets the environment for the ui code, also the calculated something or function what you created need to set in here. 

5.When you had finished the ui and sever, you need to create the global to contain these two codes.

6.Save the ui, server, global code in R.(ex: ui.R, server.R, global.R)

7.How to upload to website and show it on the website. You can see the ppt which create by myself that you clearly know how to do
