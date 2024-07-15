# Fly
// Function to greet the user
function greetUser() {
    // Prompting the user for their name
    let userName = prompt("Enter your name:");

    // Checking if the user entered a name
    if (userName) {
        // Constructing the greeting message
        let greeting = `Hello, ${userName}! Welcome to our website.`;

        // Displaying the greeting message
        alert(greeting);
    } else {
        // Handling case where user did not enter a name
        alert("Hello! Welcome to our website.");
    }
}

// Calling the greetUser function to start the interaction
greetUser();
