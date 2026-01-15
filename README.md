What did you learn about using fragments and navigation components?

I learned that fragments are basically reusable screens and the Navigation Component makes switching between them easier through the nav_graph.xml. It also helps manage the back stack automatically, so I didn’t have to do it manually.

How did you make your UI adaptive to screen size or orientation?

I used different layout folders like layout-land and layout-sw600dp so the UI adjusts for landscape and tablets. ConstraintLayout and scrollable content helped keep things readable on smaller screens.

What challenges did you face when combining Bottom Navigation and Tabs?

The tricky part was understanding that Bottom Nav is for main pages while Tabs are inside one page. Setting up ViewPager2 with TabLayout took trial and error, especially with fragment lifecycles and keeping everything from crashing.
