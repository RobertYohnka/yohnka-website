# yohnka-website
This is a project that will become part of my fullstack portfolio.  
Thank you to John Sickles, Brian Mui.

Include the following elements.
    *Done - This project was submitted via GitHub* GitHub project with a task board
    *Done - Planning tickets are being checked off as I go* Detailed planning tickets wtih task description for each one
    *Done - Most recent commits made 2/28/2024* Updated GitHub repo with new commits
    An updated website with:
        *Done - Display and Float properties change the layout based on screen sizing* improved layouts using CSS grid/flex
        proportional units
        *Done - Links at the top now interact with mouse via :hover* dynamic syling with hover effects
        *Done - Form works and opens success pages at which point javascript runs* A contact form (id=form) with the following
            *These specific fields*
                *Name*
                *email*
                *Message*
                *Submit button (id=submit type=submit)*
            *The correct attibutes is somewhere on the website*
            *Functionality that when submitted should redictr to another HTML file containing a success message*
            *A functioning submit button.*

        *Done-success.html is active* Add a "success" page (success.html)*

        *Done - JS files created* Add a js file with these details (remember to add js script to html):*
        
        const form = document.querySelector('#form')
        const submitButton = document.querySelector('#submit')
        form.addEventListener('submit', (e) => {
            submitButton.disabled = true
            e.preventDefault()
            window.location.href = window.location.origin + '/success.html'
})
        setTimeout(() => {
            window.location.href = window.location.origin
        }, 5000)