# Components Library

Introduction to CSS components and how to build your own library

### Components

Lego blocks for front end
Set templates
Can build nearly any website using these.

Examples of components:
- containers 
- buttons
- avatars
- banners
- cards
- forms
- footers
- navigation bars

##### Containers
margin(top, right, bottom, left) - 4 inputs
margin(all) - 1 input
margin(top&bottom, sides) - 2 inputs
margin(top, sides, bottom) - 3 inputs

##### Avatar

http://source.unsplash.com/random/300x300 - avatar image creator

##### Tools
<div style="display: flex;"> - makes elements flexxxxible

	put elements within div, next to each other instead of on top of eachother (block):

		display: flex;
		justify-content: space-between;
		align-items: center;
		height: 100px;

	make page body responsive to resizing:
		
		height: 100px;
		flex: 1;