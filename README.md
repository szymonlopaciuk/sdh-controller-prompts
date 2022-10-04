# Steam Deck Handheld - Controller Prompts

---

### dev info

* the "view layout"<sup>1</sup> and "edit layout -> assign button"<sup>2</sup> screens could be edited: but the former is a data: img as a background image, and the latter is an inline svg in the html
  
  * these could be fixed with `display: none;` and `::after`, but i don't think it's worth it
  1. ```html
     <div class="controllerconfiguratorsummary_BackgroundController_rlz-U"></div>
     ```
  
  2. ```html
     <div class="controllerconfiguratorchoosebinding_Column_2Pibl Panel Focusable">
     	<svg xmlns="http://www.w3.org/2000/svg" viewBox="150 0 1120 730" fill="none" class="controllerconfiguratorchoosebinding_GamepadPreview_GENH-"></svg>
     </div>
     ```
