# Project Proposal
## Background
*Name of the project*
Planning Paper Patterns for Piecers

*Team members and their responsibilities*
Mackenzie Leake -- I am working closely with Abe Davis and Maneesh on this project. Abe and I are planning to build a small end-to-end version of our system, which we intend to expand over the summer. Toward the end of the quarter, I will sew a small sample quilt using our system.

## Project Goals
*Description of project and overall goal. What do you want to be able to make?*
The system takes an image as input, provides an interface for segmenting the image into polygons, and then generates a correctly ordered paper piecing pattern. By the end of the quarter I hope to design a quilt pattern using the system and then sew the quilt.

*What is innovative about proposal?*
Paper piecing is a popular tool in the quilting community with many known rules-of-thumb. Although sewing paper pieced quilts from existing patterns is relatively straightforward, designing patterns for this technique is quite challenging. The most difficult parts are dividing an image into the shapes that can be sewn easily and producing a valid ordering of fabric pieces. Existing systems to support this kind of pattern are poorly designed and not widely used. This quarter we plan to build a small system for designing these patterns that helps people create valid quilting patterns using this technique.

*What do you think will be the hardest part of the project?* 
I expect the hardest part of this project is handling the geometry and exposing the geometric constraints to the user. We think we have an initial grasp on defining valid and invalid seam shapes, but we need to figure out how to disallow or correct bad patterns.

## Project Plans
*Plan and milestones*: 
We have some initial sense of the geometric constraints and a plan for the system design. Our interface will take an image as input, provide an interface for segmenting the image, and then produce a valid PDF pattern. We plan to spend the next 2-3 weeks implementing a basic version of the interface, and then I will spend the last two weeks using the system to make a quilt.

*Parts and supplies needed*: 
Our project is primarily a software project so the supplies we will need are limited to fabric. I plan to purchase a fabric bundle with several different colors for my quilt (like [this](https://www.amazon.com/Robert-Kaufman-Cotton-Colors-Quarter/dp/B07DCZ4PX6 "this")) so I have some freedom to design some different types of blocks. I already have the thread, batting, and backing fabric as well as the rest of the supplies and equipment I need to sew the quilt.

*References and attributions*: 
Much of my understanding of how paper piecing works from a pattern designer's perspective comes from this book: [Adventures in Paper Piecing Design](https://www.amazon.com/Adventures-Paper-Piecing-Design-Step/dp/1617455571 "Adventures in Paper Piecing Design")
In the research literature there are a few areas of work that will likely be relevant to our project, including research in fabrication, crafting, and computational geometry. Though it tackles a different part of the quilting process, this recent project in the quilting domain is interesting and relevant: [Whole-cloth Quilting Patterns from Photographs](https://textiles-lab.github.io/publications/2017-autoquilt/ "Whole-cloth Quilting Patterns from Photographs")