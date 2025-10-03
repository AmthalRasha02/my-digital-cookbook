# my-digital-cookbook
## Welcome to my cooking journey!

# Create a branch for new recipe
git checkout -b add-pizza-recipe

# Add pizza recipe
echo "## Margherita Pizza" > pizza.md
echo "**Prep Time:** 30 minutes" >> pizza.md
echo "**Cook Time:** 15 minutes" >> pizza.md
echo "**Ingredients:** pizza dough, tomato sauce, mozzarella, basil" >> pizza.md

# Commit and push
git add pizza.md
git commit -m "Add margherita pizza recipe"
git push origin add-pizza-recipe
