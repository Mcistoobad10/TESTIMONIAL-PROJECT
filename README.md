# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


 
## OVERVIEW
This is/was a challenge from front-end mentor requiring the participants to design a testimonial. The result of the one I created can be seen in the 'screenshot.png' file.

## SOLUTION
My solution can be accessed through the following URL: 

### Links
Github: URL(https://github.com/Mcistoobad10/TESTIMONIAL-PROJECT.git)



## MY PROCESS
For the overall layout of the page i used flex-grid while for styling the internal elements of each card I used flex-box.

There are two methods which could have been in relation to flex grid. One using the 'grid-template-areas' property on the parent container to create a 4x2 column(details in the css file). Then use the 'grid-area' property on each of the children to assign them to their respective areas on the grid. This is shown in the main/master branch.

The alternative method was/is to use 'grid-template-columns' property assigned to 'repeat(4,1fr)' to create 4 columns of equal size. Then I used the 'grid-column' property(values look like: 1/3 or 2/4) to determine how wide each box should be. This method is shown in the "alternative" branch of my code.

## USEFUL RESOURCES.
TRAVERSY MEDIA (https://www.youtube.com/@TraversyMedia) for learning flex-box and flex-grid.

## AUTHOR DETAILS.
Aaron McCarthy 
Email-address: @mccarthymutebi@gmail.com
