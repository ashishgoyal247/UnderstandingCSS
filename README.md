This repository will contain all concepts and facts which will help to understand CSS better.

1. Difference between Padding and Margin:
   Padding is the extra space inside the control whereas Margin is extra space outside the control. So padding is how much space an element wants to keep within the border and margin is the space outside the border.

   Padding cannot be negative but margin can be negative.

   Margin accomodates the gap by pushing adjacent elements away from it. Padding accomaodates gap by growing or shrinking size of content inside it.

   By default, padding will increase the size of the element to accommodate the gap. But if you set “box-sizing: border-box” on the element, then it will shrink the size of the content inside the element to accommodate the gap.

   Increasing padding increases size of element hence increases size for click and hover.
   
   #TODO: Read more about it
   Top/bottom margins are collapsible:
   So if you have a 20px margin at the bottom of an element and a 30px margin at the top of the next element, the margin between the two elements will be 30px rather than 50px. This does not apply to left/right margin or padding.

    If an element has a border around it, padding will give space from that border to the element content which appears in that border. If an element does not have a border around it,then adding padding has no effect at all on that element, because there is no border to give space from.

    Margin affects elements that both have or do not have borders. If an element has a border, margin defines the space from this border to the next outer element. If an element does not have a border, then margin defines the space from the element content to the next outer element.
    
