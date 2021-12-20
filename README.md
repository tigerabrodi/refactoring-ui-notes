# Refactoring UI Notes

## Starting from scratch

- Make sure to start designing features, and not the details such as a navigation bar. The whole point of designing in low-fidelity is to be able to move fast.

- Don't design too much. Design in short-cycles. Focus on designing the smallest useful version of each feature in order to not get too deep into the implementation. Expect every feature to be hard to build.

- Give the design a particular personality.

- Rounded sans serif for a playful look.

- Pick a color that you think fits well.

- Stick to one type of border radius. Large, medium, or none in value.

- Define systems in advance. Limit your choices.


## Hierarchy is Everything

- Instead of solely using font size to structure the page, also use colors and font weights.

- Keep it simple, try to stick to 2 - 3 colors or fonts, and not any more than that! 

- Don't go below font weight of 400.

- Don't use grey on colored backgrounds, the best thing to do is to pick a new color for a colored background.

- Instead of trying to further emphasize the element you want to draw attention to, figure out how you can de-emphasize the elements that are competing with it.

- Use labels as last resort. Labels that tell of what type a value is. The problem with such a approach is, it makes it difficult to present the data with any sort of hierarchy. 

- If you need to use labels and values, combine them into a single a single unit. You want to emphasize labels on information-dense pages.

- Most pages only have one true primary action, a couple of less important secondary actions, and a few seldom used tertiary actions. When designing these actions, it’s important to communicate their place in 
the hierarchy.


## Layout and Spacing

- Start with too much space. Space should be removed, not added. Dense UIs have their place.

- Define a spacing system. A practical one would be starting from 16px, which is also the default font size for every major browser.

- You don't need to fill the whole screen.

- Go with mobile-first approach, then bring the design over the a larger screen and adjust anything that felt like a compromise on smaller screens.

- Make sure groups of elements are explicitly seperated by i.e. borders, spacings etc.


## Designing Text

- Define a type system.

- For the best reading experience, make your paragraphs wide enough to fit between 45 and 75 characters per line.

- Using font sizes for hierarchy, sometimes it is better to align em on the baseline.

- Not every link needs a color.

- Align with readability in mind.


## Working with color

- Ditch hex in favour of hsl. Hue is a color's position on the color wheel. Saturation is how colorful or vivid a color looks. hsl(hue, saturation in percentages, brightness in percentages).

- Good color palette can be broken down into three categories. Greys (neutral colors), Primary colors and Accent colors (communicating different things to the user).

- When creating palettes, change the hue by 20-30 degrees, and the brightness only very slightly in order to keep the color's strength.

- Saturation when creating greys.


## Creating Depth

- You can create a depth by using box-shadow. Color sample: hsla(0, 0%, 0%, .2).

- Simulate the real-world.

- Usually 5 shadows are enough.

- Shadows can have two parts, in order to achieve a more realistic view.

- Overlap elements to create layers can be a good way to create depth. May not be suitable for elements that don't contain images.


## Working With Images

- If using background images, considering adding an overlay due to the contrast. You could also colorize it using blend mode, that way it can fit better with the colors of yours.

- When it comes to icons make sure to not scale them and instead enclose them in another shape.

- Be aware of content that the user uploads, you can for example use an inner shadow on the image to avoid it clashing with the background.


## Finished Touches

- You don't have to add new features, you can supercharge what is there, by for example instead of using bulletpoints for a list, use icons. Basically, supercharge the stuff that look a bit too normal :3

- Add color with accent borders.

- If you’re designing something that depends on user-generated content, the empty state should be a priority, not an afterthought.

- Empty states are a user’s first interaction with a new product or feature. Use them as an opportunity to be interesting and exciting — don’t settle for plain and boring.

## Images for Reference

### Shadows

![Box Shadows system design](https://user-images.githubusercontent.com/49603590/146722418-321f0ef1-7e54-4f4e-8882-f00594e271fd.png)

### Sample of component that feels pushed into the page

![Example of component that feels like it is pushed down into the page](https://user-images.githubusercontent.com/49603590/146722421-86f02e94-a56a-4157-85d1-e14b150efe32.png)

### Font system

![font system design](https://user-images.githubusercontent.com/49603590/146722423-c26ac1ea-03f1-49cc-a11c-01d9eb42309d.png)
