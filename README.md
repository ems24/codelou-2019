# codelou-may19

This project is about my favorite movies. It just includes movie posters.

Custom CSS I created include: 
.image-3 {
    grid-column-start: 5; 
    grid-column-end: 7; 
    grid-row-start: 1; 
    grid-row-end: 7;
}

For image-3 I told it where to appear on the grid from column line starting at 5 and ending at 7 and row 1 to 7 for height. 

Custom JS: 
document.querySelector('.hamburger-menu').addEventListener('click', () => {
  document.querySelector('.nav-wrapper').classList.toggle('change');
});

.hamburger-menu and .nav-wrapper is what document.querySelector is looking for, and when they're called on it creates a animation that changes the menu in the second line to add interactivity to the page. The menu is known as the hamburger-menu. 
