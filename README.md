Download Link: https://assignmentchef.com/product/solved-enel200-tutorial-6-assembly-bom-drawings
<br>
<strong>    Assembly/BOM Drawings </strong>

Assembly drawings are necessary for manufacturing because they show what parts are used in a product and how the parts fit together. Usually an assembly drawing includes a BOM (Bill of Materials), and as a result are often called BOM drawings. If a BOM is included on the drawing the terms <em>assembly drawing</em> or <em>BOM drawing</em> are synonymous. The BOM is a table which contains a list of all the part names and numbers, the quantity that are used, and sometimes other information for quick reference, such as the part material.

Dimensions are sometimes included on assembly drawings, but these are only those that relate to the assembly, and never dimensions for parts. An example of this would be a gear that is to be press fit onto a shaft at a certain location. It is correct to put a dimension on the assembly drawing that defines how far from the end of the shaft the gear should be, but it is incorrect to put any dimensions on the assembly drawing that define the size or shape of the gear or shaft themselves. <strong>All dimensions that are required for producing a part belong on the part drawing and must not appear on the assembly drawing</strong>. Often an assembly drawing does not have any dimensions because they are not required. In the previous example, if the shaft had a shoulder on it which the gear was pushed up to then there would be no dimension required. <strong>If they are not required, it is perfectly acceptable (and otherwise wrong) to have an assembly drawing with no dimensions at all</strong>.

<strong>Goals </strong>

<ul>

 <li>Understand the role of assembly drawings</li>

 <li>Know how to create assembly drawings</li>

 <li>Be able to lay out an assembly drawing in a considered way</li>

 <li>Create a BOM table and balloon part identifiers</li>

 <li>Create exploded view of assemblies and save view orientations for use on drawings</li>

</ul>

<strong>Exercise 1:           Engine Assembly Drawing </strong>

Even though the content and the purpose of assembly drawings are quite different to part drawings, they are created in exactly the same way in SolidWorks.

Select <em>New</em> from the file menu and choose the UC Drawing Template.




Because the use of assembly drawing is different to part drawings, the views shown on the drawing are not necessarily the same. The views focus on showing where parts go in the assembly, and the detail relationship with other parts. A range of different view types can be used to show this information:

<ul>

 <li>Orthographic projection</li>

 <li>Sections</li>

 <li>Isometric/pictorial</li>

 <li>Exploded</li>

</ul>

The goal when designing the layout of an assembly drawing is to <strong>minimise the number of views required to communicate what parts are there, where they go, and how they fit together</strong>. It might be quite easy to show everything by including many views on the drawing sheet, but an excessive number of views clutters the drawing and makes it harder to read.

All of these view types we have encountered with the part drawings, except the exploded view, which are unique to assembly drawings. This type of view shows the parts of an assembly in a manner in which they are separated apart so it becomes clearer what parts are there, but not necessarily how they relate with each other. We’ll begin with an exploded view of the engine.

The example exploded view is what we are aiming to be able to show on the drawing. The assembly is orientated in a sensible way (right way up and with the front angled slightly toward us), and the parts are separated enough to show all of the individual parts.

Each part is positioned in a way that is suggestive of the order in which the parts would go together. The parts which would be fitted to the assembly last are furthest away, so for example the connecting rod and piston would be fitted before the cylinder head is fitted, so the cylinder head is furthest away.




It’s important to realise that exploded views are only a graphically modified version of the SolidWorks assembly, and don’t actually change the construction of the assembly at all. All of the assembly mates are still there, but when we explode the assembly it <em>temporarily</em> allows the parts to move without obeying the mates.




The exploded view state is created in the assembly modelling environment, so open the engine assembly which you have previously made. Select <em>Exploded View</em> from the <em>Insert</em> main menu.




The explode dialogue appears in the Feature Manager area, and is ready for you to select the first part, or parts, to be moved. An exploded view is made up of one or more explode steps, with each step representing a movement of one or more parts. The process for creating each step is:

When you drag the parts into their new display position, remember that the objective of the explode is to effectively take a snapshot of it in a particular orientation to display on the drawing sheet.  This means that it is important to get the spacing between the parts so that they look nicely spaced when in the orientation which will be shown on the drawing. Following from this it makes sense to perform the part moving operations while the assembly is in that operation, so you can assess how it will look as you do it.

After you have positioned some or all of the parts you will no doubt notice that the position of some could be improved. You could create more explode steps to keep moving the parts, but a better solution is to go back and edit the steps already created. The following example illustrates this.

As shown, the assembly explosion steps have been completed (one step for each part), but it has been found that the cylinder head and piston are not high enough to allow room for the connecting rod to completely come out the top of the engine.

Look in the explode dialogue and notice the list of Explode Steps. There should be one to represent each part you have moved.

In this case Explode Step6 has been selected, which in turn has highlighted in the Graphics Area the position.

Repeat this as many times as you need to in order to get the parts sitting in the position you want them.

If you inadvertently create additional explode steps you can easily get rid of them just by right clicking on them and selecting <em>delete</em>.

Once you are happy with the positions of the parts click the green tick at the top of the Explode dialogue.

The view shown in the Graphics Area can be collapsed (back to its original state) and exploded by toggling in the dropdown menu found in the Configurations tab in the Feature Manager Area. Notice above the Feature Tree there are separate tabs, by default the feature tree tab is shown, but change this to the Configurations tab. Expand the items in Configurations tree until you see the ExplView1 item and then right click on this. Depending on whether the assembly is currently exploded or collapsed, the dropdown will show either one. In this case select <em>Collapse</em> to return the assembly to its original state.

Because we want to show the exploded view in a certain orientation on the drawing, which likely won’t be one of the standard views available, it is convenient to save the view in the assembly model, so that it will be available to use in the drawing.




Make sure the orientation of the assembly in the Graphics Area is as you want it to be shown on the drawing, and then select <em>New View</em> on the Orientation popup. Enter in the name <em>dwg explode</em> and press OK to save the view. You can now use this saved view to go back to this orientation quickly within the modelling environment, and it’s also available in the drawing environment for creating views.

Now that the exploded geometry has been created and view orientation saved, return to the assembly drawing file so that we can make use of these.

Use the <em>Model View</em> tool in the <em>View Layout</em> tab of the Command Manager to create a new view on the drawing sheet.  Double click on the <em>model car engine</em> item in the Open documents selection box, and the Model View Dialogue changes to that shown to the right.

Select the <em>Show in exploded state</em> item.

Select the <em>dwg explode</em> orientation.







Check the other settings are as shown in the example.

Set the scale to 2:3, and then click in the Graphics Area to position the new view. If it all looks OK click on the green tick at the top of the Model View dialogue to accept this new view.













The drawing sheet should look similar to the example, with a line drawing of the exploded assembly showing all parts separated with an approximately even spacing.

Note that your title block details, such as the drawing title, may not be completed with appropriate values. <strong><u>Remember for</u> <u>part drawings the</u> <u>information for the title block was all stored in the Custom Properties table for the <em>part</em>. Similarly,</u> <u>this information for the assembly drawing is stored in the Custom Properties table for the</u> <em><u>assembly</u></em><u>.</u></strong>

Open the assembly and select <em>Properties</em> from the <em>File</em> menu to bring up the Summary Information popup window. Select the <em>Custom</em> tab and enter in the values in the <em>Value/Text Expression</em> column. Just as for the part custom properties, do not alter the NUMBER item as this is set so the file name becomes the drawing number.

Note that for the assembly the Material and Finish are set to SEE PART DRAWINGS. Because there are likely a number of materials and surface finishes in an assembly it doesn’t make sense to specify these here.

Return to the assembly drawing and you can see that the title block will have updated to include the information you have just added.

Now that we have a view of the assembly on the drawing we can add the BOM table to list the parts.

Select  <em>Bill of Materials</em> in the dropdown menu from the <em>Tables</em> item in the <em>Insert </em>main menu.

The first thing that is required is to tell SolidWorks which assembly we want the BOM created for. This is done by selecting the view of the assembly in the Graphics Area.

The Bill of Materials dialogue opens in the Feature Manager area, wherein there are various setting for determining how the BOM will be displayed. Accept the default settings and click on the green tick.

A BOM table will be generated, and can be placed by clicking in the Graphics Area to define where you want it.

The BOM table can go anywhere on the drawing, but in this case we’ll place it just under the revision table.




The BOM lists all of the parts, but this isn’t very useful for the reader if they don’t know which of the parts is which in the graphical views. To identify the parts, according to their ITEM NO in the BOM, we use labels called balloons. Obviously the labels get their name because they always have a circle around them and a leader line coming away from the circle. The circle clearly identifies the numbers as part identifiers, as opposed to dimensions or any other numbers shown.




To create the balloons, select the <em>Balloon</em> tool from the <em>Annotations</em> dropdown menu in the <em>Insert </em>main menu.







In the Graphics Area, click on each part in the exploded view in turn and then click again to next to the part to define the position for the balloon. The balloon will be automatically populated with the item number associated with that part.




Arrange the balloons in a tidy way by, as much as possible, having the balloon circles sitting vertically above each other, or horizontally in rows. Also try to have the lines off the balloons so they are all on similar angles.

We now know clearly what parts are in the assembly, how many of each there are, what they look like, and approximately how the assembly would fit together. To improve the reader’s knowledge of how the parts relate to each other we’ll create some orthogonal views with sections. This is done in exactly the same way as it is for parts.




Use the <em>Model View</em> tool to insert a view of the engine assembly as shown. You will need to remove the tick next to the <em>Show in Exploded State</em>, otherwise the orthographic views will be exploded as well.

Use the Section View tool to create a section view through the middle of the engine assembly.

This is the same as doing it for a part section, but when performed on an assembly a popup window will appear after you have drawn the section line. The popup is giving you some additional options that are relevant for the assembly, including the ability to nominate parts that are not going to be sectioned. For example you should select any shafts, because they are never sectioned. There is also a check box to exclude all fasteners (if the fastener was created as a fastener part from the toolbox).

Note each part has a <em>hatching</em> ticked in the <em>Section view</em> dialogue as shown above.

This section shows some useful information about how the parts fit together, but for someone who is not familiar with the layout of engines it may still be unclear about the relationship between the connecting rod, crankshaft, and piston. To improve this, create another section view through the middle of the connecting rod.

To complete these views, add centrelines. Note that there are no dimensions required, and we do not need to repeat the allocation of balloons. These three views all add valuable information to the drawing just as they are. Overall this drawing now meets our basic objectives of communicating <strong>what parts are there, where they go, and how they fit together.</strong>