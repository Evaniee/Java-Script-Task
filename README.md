# Part 1
1. Change the colour of the Item Cost Calculator heading to darkblue when it is hovered over.
    - When the mouse is no longer hovering over the heading it should revert back to its previous colour darkslategray.
    - Note: Try to use JavaScript to change the colour on hover instead of only CSS.
# Part 2
- Validate the input field for shipping type to ensure the entered value is either "standard" "priority" or "same day".
    - If not provide relevant feedback to the user in the HTML element with the ID of shippingTypeFeedback.
    - Use JavaScript to change the colour of the feedback message to red.
- Clear any feedback messages when the user enters a valid input into the form.
# Part 3
- Calculate the cost of shipping based on the shipping type.
    - If the shipping is "same day" add a £10 shipping cost.
    - If the shipping is "priority" add a £5 shipping cost.
    - If the shipping is "standard" do not add any shipping cost.
- Calculate the total to be paid, including shipping cost and display it to the user, rounded to 2 decimal points in the HTML element with the ID of totalWithShipping
- Calculate the amount to be paid per installment (assuming equal splits of installments) and display it to the user in the HTML element with the ID of perInstallment
# Part 4
- Move the wrapper box 500 pixels to the right when "Move right" is clicked.
- Move the wrapper box back to its original position when "Move left" is clicked
- When the "Close" button is clicked clear the page of all content and display a new message saying: "Thank you for using the calculator" inside a h1 element.