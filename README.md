# JS Link for Web Parts – A Quick Functional Primer
http://www.idubbs.com/blog/2012/js-link-for-sharepoint-2013-web-partsa-quick-functional-primer/
JS Link is a new web part property in many SharePoint 2013 web parts.  It allows users and developers to create Client-Side Rendering (CSR) solutions within SharePoint 2013.  In other words, it allows alternate formatting, data and functionality to be manipulated within a web part.  It is one approach that will help replace the data view web part (DVWP) functionality that was used in SharePoint 2010 and SharePoint Designer 2010.

DVWP > 

#JSLink and SharePoint 2013 – How to Get Started
https://www.dynamics101.com/jslink-sharepoint-2013-get-started/
http://www.learningsharepoint.com/2013/03/31/uploading-javascript-js-files-as-javascript-display-template-in-sharepoint-2013/

# CSR-JSlink-samples




** Client-side rendering (JS Link) code samples **
JSLink files have the ability to quickly and easily change how a list views and forms are rendered. More specifically how the fields in that list should be displayed. I wrote the following code samples to be easy to understand and to achieve learning purposes.

Reference: 
https://code.msdn.microsoft.com/office/Client-side-rendering-JS-2ed3538a

Those samples help you learn how to customize a field type by using the Client-Side Rendering (also called CSR, JS Link) technology in SharePoint 2013.
 
Overview
Client-side rendering is a new concept in SharePoint 2013. It’s provides you with a mechanism that allow you to use your own output render for a set of controls that are hosted in a SharePoint page (list views, display, add and Edit forms). This mechanism enables you to use well-known technologies, such as HTML and JavaScript, to define the rendering logic of custom and predefined field types.
JSLink files have the ability to quickly and easily change how a list views and forms are rendered. More specifically how the fields in that list should be displayed.

Note: I wrote those code samples to be easy to understand and to achieve learning purposes, because of that I avoided using complex code and controls. In the same time I tried to present real world examples as much as possible.
 
How to deploy the JSLink templates
You can deploy those JSLink files in many ways, you can use OOTB, LIST schema PowerShell or code.  
I describe in the samples below how to deploy JSLink files using OOTB techniques, 
but if you want to know more about JSLink deployment methods, I recommend this article by Andrei Markeev. 
http://www.codeproject.com/Articles/620110/SharePoint-Client-Side-Rendering-List-Views

Before proceeding with the samples, You have to upload the JavaScript code files on your SharePoint 2013 site. 
You can upload to any SharePoint storage document library, _layouts folder or IIS virtual folder, 
But in the below deployment steps I’m supposing you will upload the JSLink-Samples folder to the site collection **Style Library**.
 
Sample 1 (Priority color)
Let’s start with a simple example, This JSLink sample allows you to change the priority field text color based on the task priority level (High, Normal and Low).
Read More ... http://code.msdn.microsoft.com/office/Client-side-rendering-code-0a786cdd
 
Sample 2 (Substring long text)
Our next sample, Will show you how to make the announcements body text shorter and display the whole announcements body text as a tooltip.
Read More ...
 
Sample 3 (Confidential Documents)
This JSLink sample will show how to add an icon beside confidential documents name. This icon is added to the document name based on the Confidential field (Yes/No) value.
Read More ... http://code.msdn.microsoft.com/office/Client-side-rendering-code-97e27fa1 
 
Sample 4 (HTML5 number input )
This JSLink sample will demonstrate how to use HTML5 input control Instead of the old HTML in SharePoint New and Edit forms.
Read More ...
 
Sample 5 (Percent Complete)
This JSLink sample will show how to add rendering logic for the Task list Percent Complete field, this code will change the file render to be displayed as a progress bar in View and Display forms, and as a scroll input in the New and Edit forms.
Read More ...
 
Sample 6 (Accordion)
This JSLink sample will show how to change rendering logic for the whole List View. This sample will read the Title and Description fields’ values and render the fields in an accordion style view.
Read More ...
 
Sample 7 (Email Regex Validator)
This JSLink sample will show how to add Regex validation to input fields inside New and Edit forms.
Read More ...
 
Sample 8 (Read- Only SP Controls)
This JSLink sample will show how to use and utilize ready sharepoint javascript libraries to make form fileds uneditable. 
Read More ...
 
Sample 9 (Hidden Field)
If you browse this code sample, you will learn how to use OnPostRender template functionality.
Read More ...
 
Sample 10 (Hide Empty Column)
If you look at this code sample, you will see how to create the CSR Context object, and how to access all reternd list data, then you can use the JQuery to change the view html.
Read More ...
 
Sample 11 (Form Tabs)
This is an advance sample, it will help you to learn how to create the embed css inside your CSR files.
Read More ...
 
Sample 12 (Repeater)
This is an advance sample, it will help you to learn how to utilize your javascript skills to build advanced SharePoint list forms.
Read More ...
 
Sample 13 (Fully customized forms with CSRListForm)
This Client side rendering code sample will help you to work with CSRListForm and build your sharepoint list forms form scratch and use any form layout and design that you want. .
Read More ...
