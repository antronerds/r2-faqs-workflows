<a id="r2_workflows"> </a>


Workflows
===========================================

*Typical workflows that explore the combinations of analysis possible in R2*

Workflow: Generate a direct link to a public dataset in R2
-----

If you would like to include a direct link to a public dataset in R2, then you can follow the procedure described here.

1.  Make sure that you are NOT logged in with your own account. So log off in case that you are logged in.
2.  Navigate to the dataset to which you would like to create a link. You can use the 'change dataset' link in 'box 2' for this.
3.  Finally, click on the 'goto main' link in the upper left corner of the screen.
4.  The web address that will now appear can be copied directly and be provided as a refeerence to the dataset.


Workflow: Marking samples in a YY or XY plot
-----

1.  Marking a single sample

	With the ‘samples to mark’ option, you can make samples stand out. The easiest is marking a single sample using the R2 default setting. Make sure that you add a samplename (e.g. itcc0288) from the current dataset and press ‘redraw’. The indicated sample is now highlighted by an orange line.

<form name="test" action="https://hgserver1.amc.nl/cgi-bin/r2/main.cgi" target="R2" method="POST">
  <input type="hidden" name="option" placeholder="display2">
  <input type="hidden" name="table" placeholder="ps_avgpres_nbadam88_u133p2">
  <input type='hidden' name="graphtype" value="XY">
  <input type='hidden' name="factor" value="209757_s_at">
  <input type='hidden' name="factor2" value="209757_s_at">
  <button type="submit">Show me</button>
</form>

2.  Types of markings

	We can change the type of mark by changing the mark method from ‘dot’, to one of the other methods. ‘circle’ will draw an open circle around the sample; epicenter will draw a range of larger circles around the marked patient; and ‘arrow’ will place an arrow pointing to the sample.
	

3.  Coloring and marking multiple samples

	Marking more than 1 sample is achieved by ’,’ separation (e.g. itcc0288,itcc0021,itcc0013,itcc0132).
Thus far all have been of the same color. We can also change the color of the marker by adding ‘:’ followed by a hex color (e.g. itcc0288,itcc0021,itcc0013,itcc0132:00ff00).


4.  Defining sample groups

	The previous example made all 4 samples green. We can also define groups and define different colors to every group. Groups are separated by ‘;’. To color our previous example with 2 groups, each having a different color, we define the following: itcc0288,itcc0021:ff00ff;itcc0013,itcc0132:00ff00




Workflow: Array data analysis; find groups
-----

-  A bulleted list is created by a minus, plus or asterisk followed by two spaces
-  Next item
  -  Subitem by two spaces


Workflow: 
-----

1.  This will give a numbered list
2.  Next item
	
	To continue numbering after enter or figure, indent the whole paragraph with a tab, or more tabs when in sublist
	
3.  And the third continues

Any text between restarts numbering

4.  Next list
  1. Two spaces create a sublist
  *  They can be mixed

Images are formatted as follows:

![Figure 11: the extra settings Panel](_static/images/OneGene_Adapting.png)

[**Figure 11: the extra settings Panel**](_static/images/OneGene_Adapting.png)

Note the enter between the lines; this is to guarantee proper formatting in pdf

The Did you know box is formatted as follows

---------
  ![](_static/images/R2d2_logo.png)**Did you know box**


> *Three or more minusses preceded by a return create a line; the > sign in front of a paragraph indents the whole paragraph and the single asterisks put it in italic*

---------

You'll have to get used to the use of spaces and enters in Markdown; these are used for formatting


  Two spaces at the start of a line creates a paragraph
Type on here below  


  







