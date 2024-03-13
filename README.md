# Inwiyounes
This is an app that makes it easy to use the Internet.
def convert_star_rating(six_star_rating):
    # Define the mapping from 6-star scale to 3-star scale
    conversion_map = {6: 3, 5: 3, 4: 2, 3: 2, 2: 1, 1: 1}

    # Check if the input rating is valid
    if six_star_rating not in conversion_map:
        return "Invalid input rating. Please provide a rating between 1 and 6."

    # Convert the rating and return
    return conversion_map[six_star_rating]

# Example usage:
six_star_rating = 4
print(f"A 6-star rating of {six_star_rating} converts to a 3-star rating of {convert_star_rating(six_star_rating)}.")
