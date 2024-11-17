# H5P.Animator: Tutorial
_H5P.Animator_ is a tool you can use to create simple animations. It does not compete with highly sophisticated tools like Blender or After Effects, but rather on the level of what many people do with PowerPoint. It is based on the [H5P](https://h5p.org) framework.

Here's a short tutorial. We're going to create a very simple animation with three different elements. So, here we go!

Start by creating a new H5P content and choose Animator. You will be greeted with its editor, which should look like this.

![H5P.Animator: Editor](assets/animator_tutorial_editor.png?raw=true)

## Change the background
1. Locate the _Background_ options and click the label.
The field will expand to reveal the options.
2. Click the color picker of the _Background color_ option, select a pink hue, and click the _Choose_ button.
The canvas background will now use the pink color.

![H5P.Animator: Background options set](assets/animator_tutorial_background.png?raw=true)

## Add a text element
1. Locate the button labeled _A_ and click it to add a text item.
An overlay will open with all the options for that item.
2. The text element is very simple. It just contains a text box. Click on it and type `Hello,`.

![H5P.Animator: "Hello" entered in text field](assets/animator_tutorial_text_hello_1.png?raw=true)

3. Select all the text and find the Font Size button in the toolbar above the text box (an _A_ with an arrow next to it). Click the button and then click _175%_ in the drop-down menu that opens.
Your text will now appear slightly larger.
4. On the toolbar, find the _Text Alignment_ button (four horizontal lines). Click on this button and choose _Align Right_ (four bars will be aligned to the right).
Your text will now be aligned to the right side of the text box.
5. Locate the _Done_ button and click it.
You will now see your text element on the canvas.

![H5P.Animator: "Hello" text element on canvas](assets/animator_tutorial_text_hello_2.png?raw=true)

## Arrange the text element
1. Click on the text element to select it.
You will see a shortcut menu above the element and a blue border around the element. The border has white squares that mark resize points.
2. Use the resize handles to resize the element so that its size better matches the size of the text.
3. Drag the element until it is roughly centered vertically with its right edge near the center.

![H5P.Animator: "Hello", text element centered on canvas](assets/animator_tutorial_text_hello_3.png?raw=true)

## Copy element to create a 2nd text element.
1. Make sure your text item is selected by clicking on it.
2. Find the _Copy_ button in the context menu of the element (two stacked paper documents). Click this button.
The rightmost button of the content toolbar, the _Paste_ button (clipboard with a sheet of paper) is now no longer disabled.

![H5P.Animator: main toolbar](assets/animator_tutorial_toolbar.png?raw=true)

3. Click the Paste button.
A copy of your text element is placed on the canvas.
4. Click on the item you just pasted on the canvas.
It will be selected.
5. Click the _Edit_ (pencil) button.
The options for this text item will open.
6. Replace the text with `world!`.
7. Find the _Text Alignment_ button and change the alignment to _Align Left_.
The text is now left-aligned.
8. Find the _Done_ button and click it.
Your element on the canvas will now say "world!
9. Move the element so that together with your first element it forms the sentence "Hello, world!

![H5P.Animator: "Hello, world!" visible on canvas](assets/animator_tutorial_text_hello_world.png?raw=true)

## Animate an element
1. On the action toolbar, locate and click the Toggle List View (Bulleted List) button.
The list view will open and the _Elements_ panel will appear. This panel contains two items, one for each of your text items. Note that you can also click on an item here to select that element.

![H5P.Animator: Elements panel open](assets/animator_tutorial_elements_panel.png?raw=true)

2. In the list view, locate the _Animations_ tab and click in.
The Animations panel will become visible, but will only contain a disabled _+_ button.

![H5P.Animator: Animations panel open](assets/animator_tutorial_animations_panel.png?raw=true)

3. Select your first text element with the label "Hello,".
The element is selected and the _+_ button is enabled.

![H5P.Animator: Animations panel with active "+" button](assets/animator_tutorial_animations_panel_active_button.png?raw=true)

4. Click the _+_ button to add an animation to the selected text element.
The animation options for the element will open.

![H5P.Animator: Animation options](assets/animator_tutorial_animation_options.png?raw=true)

5. Locate the _Effect_ drop-down menu and note that it is set to _Fly in_ by default. This is the effect you want your animation to use. Leave it that way.
6. Locate the _Direction_ drop-down menu. It contains additional options for the _Fly In_ effect. By default, it is set to _From the left_, which means that your element should fly in from outside the view to the position where you placed it. Don't change this value.
7. Locate the _Start with_ drop-down menu. It allows you to choose when the animation should start in relation to the previous animation. Since this is the first animation, you can ignore this option.
8. Find the _Duration_ option and change the value to 5.
9. Locate the _Done_ button and click it.
The animation options will close and your animation panel will now contain one element. The item will tell you what element it is attached to ("Hello,") and also tell you in a nutshell what it does ("Fly in - After previous - 5s").

![H5P.Animator: Animations panel with one item](assets/animator_tutorial_animations_panel_one_item.png?raw=true)

## Preview the animation
1. Locate the _Preview_ button (TV screen) and click it.
A preview overlay will open to show you how the user would experience the animation in a player.

![H5P.Animator: Preview](assets/animator_tutorial_preview.png?raw=true)

2. Locate the _Play_ button (triangle) and click it.
You will see the "Hello" text element fly in from the left within 5 seconds.
3. Find the _Done_ button and click it.
The preview will close.

## Animate another element
1. Select the "world!" text element.
2. Click the _+_ button in the Animation panel.
The animation options for this element will open.
3. Locate the _Direction_ drop-down menu and change it to _From right_.
4. Find the _Start with_ drop down menu and change it to _Previous_. This will make the animation start with the previous animation in the Animation Panel - the one for the "Hello," text element in your case.
5. Find the _Delay_ option and change the value to 2. This will make the animation start with the previous one, but with a delay of 2 seconds.
6. Find the _Duration_ option and change the value to 3. Together with the delay, this animation will then last 5 seconds, ending at the same time as the "Fly-in" animation of the "Hello," text element.
7. Locate the _Done_ button and click it.
This closes the animation options. Notice that you now have two elements in the Animation Panel. The top animation is applied first. The other animations are applied based on their _Start With_ setting relative to their immediate predecessor.

![H5P.Animator: animation panel with two items](assets/animator_tutorial_animations_panel_two_items.png?raw=true)

## Preview the animation again
1. Preview the animation again.
Notice that none of the elements are visible at first because each of them now has a "fly-in" effect attached to it. When you play the animation, the "Hello" text element will immediately fly in from the left. The "World" text element will fly in from the right, but with a delay of 2 seconds. However, this animation will end its movement at the same time as the "Hello" text element's animation ends. Notice that the speed of the "World" text element's animation is slightly faster because of this.
2. Close the preview.

## Tweak the animation
1. Locate the submenu button (three dots) of the "world!" animation element and click it.
A submenu with more options will open.

![H5P.Animator: Animation item with options](assets/animator_tutorial_animation_item_options.png?raw=true)

2. Locate the _Edit_ option in the submenu and click it.
The animation options for the "world!" element will open.
3. Find the _Easing_ drop-down menu and change it to _Easing_.
This setting means that the animation will slow down over time. Since the speed of this animation was a little higher than the speed of the "Hello" text element's animation, this way we can make it feel like the "world" text element is trying to catch up and has to slow down at the end to avoid crashing into the other element :-)
4. Close the options.

## Add yet another element
1. Locate the _Shape_ button (empty square) on the Elements toolbar and click it.
The options for the H5P.Shape content type will open.
2. Do not change anything.
3. Locate the _Done_ button and click it.
The options will close and a white rectangle will be placed on the canvas.
4. Select the rectangle and resize it so that it is large enough to cover the other two elements.
5. Drag the rectangle over the other elements.
The rectangle now covers the other two text elements.

![H5P.Animator: Three elements, rectangle covering the others](assets/animator_tutorial_three_elements.png?raw=true)

## Change the element order
1. In the list view, locate and click the _Elements_ tab. Notice that there are now three list items: two for your text elements and one for the shape element. The items are ordered by the position of the element they represent on the canvas. The shape list item is at the top of the list and at the top of the canvas, so it covers all the other elements.
2. Drag the shape list item below the "Hello," list item.
The shape item now sits below both text items on the canvas. Note that the order of the elements on the canvas changes as you drag a list item, so you can easily control the result.

![H5P.Animator: reordered elements](assets/animator_tutorial_elements_reordered.png?raw=true)

## Hide elements
Depending on how you have resized the text and shape elements, you may now find that it is difficult to select them for resizing on the canvas because they are now stacked on top of each other. That's why you can hide elements on the canvas. We will now focus on the shape element.
1. Locate the submenu button (three dots) of the "world!" text element and click it.
This will open a submenu with more options.

![H5P.Animator: Element item with options](assets/animator_tutorial_element_item_options.png?raw=true)

2. Find the _Hide_ option and click it.
The "world!" text element is now hidden on the canvas. The corresponding element item in the Elements pane now has a gray background and a dotted border to indicate its invisible state.
Note that hiding an element does not remove it from the animation.
3. Click the submenu button of the "world!" text element again.
Notice that the submenu item previously labeled _Hide_ is now labeled _Show_. Don't click it. But if you did, you could make the item visible again on the canvas.
4. Hide the "Hello," text element as well.
Your canvas will now show only the rectangle.

![H5P.Animator: two invisible elements](assets/animator_tutorial_two_invisible_elements.png?raw=true)

## Add another animation
1. Open the Animations panel in List view.
2. Add an animation to your shape element.
The animation options will be visible.
3. Locate the _Effect_ drop-down menu and select _Fade In_.
4. Change the _Duration_ value to 3.
5. Change the _Easing_ value to _Fade out_.
6. Close the options.

## Check the preview
1. Preview the animation again.
Notice that none of the elements are visible at first because each of them now has a "fly-in" effect attached to it. When you play the animation, the "Hello" text element will immediately fly in from the left. The "World" text element will fly in from the right, but with a delay of 2 seconds. After 5 seconds, the white rectangle will fade in for 3 seconds, with a slight acceleration at the beginning and a slight deceleration at the end.
2. Close the preview.

## Save the animation
1. Locate the content's _Title_ field and add a title here.
2. Find the button to save the content and save the content.

__Congratulations! You have created your first animation with H5P.Animator and already used many of its features!__

## More things you might want to explore on your own
- Add a background image to your animation.
- Add audio to your animation
- Add a picture element to your animation.
- See what the other animation effects do.
- Try the zoom buttons, or move the mouse cursor over the canvas, then hold down the `Ctrl`/`⌘` key and use the mouse wheel.
