# Frontend Mentor Blog Preview Card Challenge

## Introduction
This challenge was both enjoyable and educational. It presented the opportunity to refine my frontend development skills while tackling the intricacies of matching a design to scale.

## Approach
To address the scaling challenge, I adopted a new method. I encapsulated my code within a `.container` div, setting its background image to the design JPEG with an opacity of 0.3. This allowed me to overlay the design while writing the CSS for the `.card` element, providing a more precise reference compared to my previous method of eyeballing sizes.

Here's the CSS that I used to do this in case you'd like to use it:

~~~ CSS:
.container {
    background-image: url(''); /* Path to the desktop design here or whichever design you're using */
    background-size: cover;
    background-position: center;
    opacity: 0.5; 
}
~~~


Initially, I experimented with the "Pixel Perfect" Chrome extension, as suggested by [Ezekiel225](https://github.com/Ezekiel225). While helpful initially, I encountered scaling issues that led me to explore alternative tracing methods. Though not a perfect solution, this approach brought me closer to achieving a 100% match with the design, providing valuable learning experiences along the way. At best, I think this way of doing it has bought me a little over 80% closer to the original. Not 100% but better than before!

## Challenges Faced
One challenge I encountered was optimizing the layout for mobile views. Through research, I discovered the versatility of using `:root` variables to scale elements uniformly. While effective for the majority of adjustments, I'm open to feedback on whether this method aligns with best practices.

Your feedback and insights are always appreciated.

Thank you,  
Taha A.
