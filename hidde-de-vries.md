# Introduction
As part of the Minor Web Development and Design, each week we have a guest lecture.
Date: 19 April 2023

Dialogs and Modals by Hidde de Vries

## Dialogs and Modals
Modals and dialogs are commonly utilized on websites to present important information or prompt users to take specific actions. 
Ensuring the correct usage of these elements is vital for providing a positive user experience. 
Hidde de Vries is a frontend developer and accessibility expert, he provides valuable definitions and tips for implementing modals and dialogs effectively.

### Modal vs. Non-modal
A modal is a type of dialog that appears on top of the main content of a website and requires the user's attention. 
While a modal is open, users cannot interact with the main content. 
On the other hand, a non-modal dialog is also displayed on top of the main content, but users can still interact with the website while the dialog is open. 
It's crucial to ensure that the main content remains inactive or inert when a modal is open to avoid user confusion or accidental interaction with elements outside the modal.

### Dismissal Methods
Modals and dialogs can be dismissed explicitly through button clicks or using light dismiss, such as clicking outside or hovering outside the element.

### Z-Index and Top Layer
The CSS property "z-index" determines the stacking order of elements, with higher values appearing on top of lower values. 
However, the relatively new "top layer" feature ensures that the content inside the top layer is always displayed on top, regardless of the z-index of other elements. 
The top layer can be useful for placing modals or other dialogs on top of the main content.

### Backdrops
Backdrops are often used in modals to create a semi-transparent overlay behind the dialog, highlighting its importance while slightly obscuring the page's contents. 
Elements inside the top layer have this backdrop built-in, and it can be styled using the "::backdrop" pseudo selector in CSS.

### Keyboard Focus Traps
Keyboard focus traps can be employed to prevent users from interacting with the main content while the modal or dialog is open. 
Focus traps make elements outside the modal untabbable, ensuring that the user's attention remains within the modal. 
It's crucial to remove the focus trap once the modal is closed, allowing the rest of the website to become tabbable again.

By following these guidelines, web developers can effectively utilize modals and dialogs, creating a seamless and user-friendly experience for website visitors.
