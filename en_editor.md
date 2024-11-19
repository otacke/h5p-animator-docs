# H5P.Animator: Editor
_H5P.Animator_ is a tool you can use to create simple animations. It does not compete with highly sophisticated tools like Blender or After Effects, but rather on the level of what many people do with PowerPoint. It is based on the [H5P](https://h5p.org) framework.

When you create _H5P.Animator_ content, it will greet you with a mix of a visual editor and some form-based settings that many H5P content types use. It will look something like this. The exact visual appearance may differ a bit depending on what kind of H5P integration you are using and what version of the H5P core the H5P integration is using.

![H5P.Animator Editor Overview](assets/animator_editor_overview.png?raw=true)

1) __General settings:__ The [general settings](#general-settings) allow you to set things like the background color or image for your animation, add an audio file, change the behavioral settings, and customize the translation of the content.
Please note that the third expandable menu item is labeled _16/9_ instead of _Behavioural settings_ due to a quirk in H5P itself, not in the content type. This is supposed to be fixed in the future.

2) __Content toolbar:__ The [content toolbar](#content-toolbar) allows you to add elements such as text, images, video or shapes to your animation.

3) __Action toolbar:__ The [action toolbar](#action-toolbar) allows you to toggle the visibility of the list view for elements and animations, zoom in and out, and preview your animation.

4) __Canvas:__ The [canvas](#canvas) area is where you will place the elements that will make up your animation.

## General settings

### Background
Here you can select a _background color_ for your animation. The background of the canvas will change accordingly. By default it is white.
You can also add a _background image_ to your animation. The background of the canvas will change accordingly. If your background image has (semi-)transparent areas, the background color will show through. If your background image has a different aspect ratio than your animation, it will be scaled to cover the entire canvas. In this case, some parts at the top and bottom or left and right of your image will not be visible.

![H5P.Animator background options](assets/animator_editor_background.png?raw=true)

### Audio
Here you can add an audio file to be used as background music for the animation.

![H5P.Animator audio options](assets/animator_editor_audio.png?raw=true)

### Behavioural settings
This is where you set the _aspect ratio_ for your animation. By default, it is 16/9, which is a common default.
You also have the option to _hide the player controls_ that the user of your animation will interact with. By default, the controls are always visible below the animation. If you choose to hide them, they will be placed above the bottom of the animation and will disappear after a moment unless the user hovers over the area with the mouse.
Here you can add a _description_ of the video that will be put above the video. It will not be visible, but can be read by screen readers.

![H5P.Animator Behavioural Settings](assets/animator_editor_behavioural_settings.png?raw=true)

### Text overrides and translations
Here you can change the text snippets that the player uses for screen readers. If a translation into your language is available, you can swap the texts here using the language drop-down menu. You can also change each text snippet yourself if you prefer a different one, or if there isn't a translation in your language yet.

![H5P.Animator text overrides and translations](assets/animator_editor_text_overrides.png?raw=true)

## Content toolbar
### Text
Clicking this button adds a text element to the canvas and opens its options.

![H5P.Animator Text Element](assets/animator_editor_text.png?raw=true)

### Image
Clicking this button adds an image element to the canvas and opens its options.

![H5P.Animator image element](assets/animator_editor_image.png?raw=true)

### Video
Clicking this button adds a video element to the canvas and opens its options.

![H5P.Animator video element](assets/animator_editor_video.png?raw=true)

### Shape
Clicking this button adds a shape element to the canvas and opens its options.

![H5P.Animator shape element](assets/animator_editor_shape.png?raw=true)

### Paste content
This button is initially disabled if there is no suitable H5P content in your browser's H5P clipboard. If there is suitable content, clicking the button will paste a copy of that content to the canvas.

## Action toolbar
### Toggle list view
By clicking the _Toggle list view_ button, you can show/hide the list view, which itself contains two panels: One for elements and one for animations. You can switch between the elements panel and the animations panel by clicking on the respective tabs.

See the [canvas](#canvas) section for details on the [elements panel](#elements-panel) and the [animation panel](#animations-panel).

### Zoom in
Pressing this button allows you to zoom into the canvas. Note that this button is disabled when you cannot zoom in any further. Note that you can also zoom in using the `+` key or by hovering over the canvas and holding down the `Ctrl`/`⌘` key while using the mouse wheel.

![H5P.Animator editor zoomed in](assets/animator_editor_zoom.png?raw=true)

### Zoom out
Press this button to zoom out of the canvas. Note that this button is disabled when you cannot zoom out any further. Note that you can also zoom out by using the `-` key or by hovering over the canvas and holding down the `Ctrl`/`⌘` key while using the mouse scroll wheel.

### Preview
When you press this button, a preview of your animation will open, behaving just like the player would. You can close the preview by clicking the _Done_ button.

![H5P.Animator editor preview](assets/animator_editor_preview.png?raw=true)

## Canvas
The canvas is where you place elements. Besides the canvas, you can also use the [elements panel](#element_panel) and the [animations panel](#animations-panel) for certain actions.

In general, you can drag elements on the canvas to any position. Clicking on an element will display its context menu, allowing you to modify the element. You can resize elements using the white squares placed around the border. You can double-click elements to edit them.

![H5P.Animator editor element context menu](assets/animator_editor_context_menu.png?raw=true)

1) __Transform:__ Click this button to display the exact position and size of the element. Click on any of the numeric values to change them using the keyboard.

![H5P.Animator editor element context menu transform options](assets/animator_editor_context_menu_transform.png?raw=true)

2) __Edit:__ Opens the options for this element.
3) __Copy:__ Copies the element to your browser's H5P clipboard, so you can paste it here or in any other H5P content type that supports the type of element you copied.
4) __Bring to Front:__ Puts the element on top of all other elements. The element's position in the element panel will change accordingly.
5) __Send to Back:__ Places the item behind all other items. The element's position in the element panel will change accordingly.
6) __Remove:__ Remove the element from the canvas. You must confirm this step. Note that any animation you have attached to this element will also be removed.

Please note that if you hide elements in the [elements panel](#elements-panel), they will not be visible here.

### Elements panel
![H5P.Animator editor list view with elements panel](assets/animator_editor_elements_panel.png?raw=true)

The elements panel gives you a list of all the elements you have placed on the canvas, stacked on top of each other in different layers. The elements in the list are ordered from highest element (the element in the top canvas layer) to lowest element (the element in the bottom canvas layer). You can change the order of the elements - and thus the layer in which they appear - by dragging the list items to the desired position. Note that the stack position of the elements on the canvas changes immediately.

If you have many elements, it may be easier to click on the corresponding list item in the elements panel to highlight the element on the canvas than to select the element on the canvas.
Each element list item has a menu that you can open by clicking the "three dots" button.

![H5P.Animator editor elements menu](assets/animator_editor_elements_menu.png?raw=true)

1) __Edit:__ Opens the options for this element.
2) __Move up:__ Moves the element up one position in the canvas layers. Note that this option is not available for the top element.
3) __Move down:__ Moves the element one position down in the canvas layers. Note that this option is not available for the bottommost element.
4) __Remove:__ Removes the item from the canvas. You must confirm this step. Note that any animation you have attached to this element will also be removed.
5) __Hide/Show:__ Will hide/show the element on the canvas. This is useful if you have many elements and want to focus on just a few. Note that the color of the list item will change to gray to indicate that the item is hidden.

### Animations panel
![H5P.Animator editor list view with animations panel](assets/animator_editor_animations_panel.png?raw=true)

The Animations panel lists all the animations you have added to your elements. Initially, the list is empty except for a disabled _+_ button at the bottom. To add an animation, select the element you want to add an animation to. The _+_ button will turn blue. When you click on it, a new animation is added and its options are opened.

![H5P.Animator editor animation options](assets/animator_editor_animations_edit_options.png?raw=true)

- __Effect:__ What effect to use for the animation. You can choose from different "entrance" effects, "emphasis" effects and "exit" effects. Each effect may have some additional options, e.g. the _Angle_ for a _Rotation_ effect.
- __Start with:__ when the animation should start relative to the previous animation. You can either choose _With previous_ to make the animation start at the same time as the previous one, or _After previous_ to make the animation start after the previous one has finished.
- __Delay:__ An optional delay in seconds. For example, if you chose to start the animation after the previous animation and added a delay of 3 seconds, the current animation would start 3 seconds after the previous animation finished.
- __Duration:__ The duration in seconds for the animation.
- __Easing:__ An easing function to determine if the speed of the element should remain the same all the time (linear), accelerate at the beginning (ease-in), decelerate at the end (ease-out), or accelerate at the beginning and decelerate at the end.

Please note that _H5P.Animator_ cannot handle multiple animations on the same element at the same time, currently. This limitation is supposed to be removed with the release of a newer version of one of the libraries that is used.

The animations you add to the animations panel form a kind of timeline. The list item at the top is the animation you want to play first, the others follow depending on when you want them to start.

Each animation list item has a menu that you can open by clicking the _three dots_ button.

![H5P.Animator editor animations menu](assets/animator_editor_animations_menu.png?raw=true)

1) __Edit:__ Opens the options for this animation.
2) __Move up:__ Moves the animation up one position, changing the order in which the animation plays. Note that this option is not available for the top element.
3) __Move down:__ Moves the element down one position, changing the order in which the animations play. Note that this option is not available for the bottom element.
4) __Remove:__ Removes the animation. You must confirm this step.

## Additional Notes
You can use the zoom buttons to zoom in and out, but you can also use the `+` key to zoom in and the `-` key to zoom out. You can also use your mouse's scroll wheel to zoom in and out by hovering over the canvas and holding down the `Ctrl`/`⌘` key.
