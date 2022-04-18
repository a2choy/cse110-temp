# Title
Theme type for BuJo settings page

## Status

What is the status, such as proposed, accepted, rejected, deprecated, superseded, etc.?  
accepted

## Context

What is the issue that we're seeing that is motivating this decision or change?  
We are choosing how much constraints we should put for the user while choosing the color theme of the bullet journal. This also affects how difficult implementing the settings page will be. 
Option 1:  
We set up 7-10 color theme, and user can choose any of them as the primary color for the website. Once user chose the primary color, we automatically calculate how we want to changing opacity of the colors to redesign our wesite
Option 2:  
A set of themes ready-defined for the users. 
Option 3:  
Using a color picker and then defining the theme using different shades of the same color. 

## Decision

What is the change that we're proposing and/or doing?
Going for option 2!

## Consequences

What becomes easier or more difficult to do because of this change?
Now we need to decide what the themes would be... another ADR!

## Alternatives  
Option 1:  
We set up 7-10 color theme, and user can choose any of them as the primary color for the website. Once user chose the primary color, we automatically calculate how we want to changing opacity of the colors to redesign our wesite
* Con:  too complicated?
Option 3:  
Using a color picker and then defining the theme using different shades of the same color. 
* Con: too much options for the user. Little constraints. 