metrocharts
===========

fork of http://modernuicharts.codeplex.com/


his project provides a small library to display charts in Modern UI Style (formerly known as Metro) in WPF, Silverlight and Windows 8 applications. You can check the charts with the Silverlight test application here: http://www.tetracon.de/charts

Available Charts

ColumnChart (ClusteredColumnChart, StackedColumnChart, StackedColumnChart100Percent)
PieChart (PieChart and Dognut)
BarChart (ClusteredBarChart, StackedBarChart, StackedBarChart100Percent)
Doughnut Chart
Radial Gauge Chart
News

2013-05-05: Release of BETA version with several bug fixes and new charts (Doughnut, Radial Gauge, improved test applications and many more)
2013-05-04: Availability of Silverlight test application via http://www.tetracon.de/charts
Screenshots

Default Layout

![0a1a45c6-d41a-43f0-b7ed-ad1f8dd24754](https://user-images.githubusercontent.com/364896/114027821-13c35d00-9878-11eb-9ef1-9f6fe91ab221.png)


Dark Layout

![968659ba-5808-467a-b250-dafb2fdcf3ab](https://user-images.githubusercontent.com/364896/114027844-1b830180-9878-11eb-9d4f-3948013448fd.png)


Custom Palette (e.g.. with gradients or mono chrome)

![7952053f-7a5a-4987-86ee-9311d7a26255](https://user-images.githubusercontent.com/364896/114027867-22aa0f80-9878-11eb-92cc-6c8334b257b8.png)


Easy Switch of Axes (same data, switched axes)

![74c85452-0b25-45ce-b83f-0d11e777a964](https://user-images.githubusercontent.com/364896/114027896-29388700-9878-11eb-87c5-5ab5c49829e0.png)


Intention 1
I needed Modern UI Charts for my own application which should run on Desktop (WPF), Web (Silverlight) and Windows 8 devices and I didn't want to use 3 different third party charting components. That’s why I created the charts from scratch and used them in the tool “SharePoint Code Analysis Framework (SPCAF)” (http://go.spcaf.com/VSGallery) which I have developed with Matthias Einig.

Intention 2
I think that XAML is the greatest way to "describe” the UI of an application via a markup language. I don’t want to miss things like data binding, styling of controls, data templates, animation of state changes, easy re-use of custom controls, design support with Blend and many more. I don’t hope that HTML5 and JavaScript are the only future for our UIs. That’s why I wanted to discover how the same XAML could be used “cross-plattform” in WPF, Silverlight and Windows 8. For the charts I wanted to use as much as possible of the same XAML code which is available on all these plattforms. So finally the code for the charts uses the lowest common XAML subset of all three worlds. Check out the sample application in this project and see how it works.

Features
The charts have been developed from scratch with keeping in mind to fully support MVVM data binding, styling, retemplating, animation, dynamic series etc.

Dynamic binding of data
Animation after loading and after changes to underlying data
Custom Color Palette
Hidable Title and Legend
Switchable series
Light and dark layout support
Configurable font size
…
Try it out
The download contains the binaries, source code and test applications for WPF, Windows 8 and Silverlight. Download the release and try it out.

Important
This code is intended to be a sample how code can be created for WPF, Silverlight and Windows8. The code is an BETA release and still may have some bugs!

Screenshot Windows 8

 
Screenshot WPF


Screenshot Silverlight


 

About the Author

Torsten Mandelkow
The charts have been developed by Torsten Mandelkow as part of a larger application. Torsten works for Microsoft in Germany and has a long experience in .NET development, especially for SharePoint. With components like the charts he wants to explore how 'hybrid' applications with XAML can be created which run on desktop (WPF), on Windows 8 and in the web (Silverlight).
Blog:     blogs.msdn.com/b/torstenmandelkow/
Twitter: @tmandelkow

