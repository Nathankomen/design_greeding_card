# design_greeding_card
A birthday greeting card web page using HTML and CSS only, in two files: index.html and styles.css.
HTML structure:
- A div with id "greeting-card" and class "card" containing:
  - An h1: "Happy Birthday!"
  - A p with class "message": "Wishing you all the happiness and joy on your special day!"
  - A div with class "card-links" containing two links:
    - "Send Card" (class "send-link", href "#send")
    - "Share on Social Media" (class "share-link", href "#share")
  - A section with id "send" containing an h2 "Sending your card..." and a p "Card successfully sent to your recipient!"
  - A section with id "share" containing an h2 "Sharing your card..." and a p "Your card was shared on social media!"

CSS requirements:
- body: Arial, sans-serif; 40px padding; centered text; brown background.
- .card: white background; max-width 400px; 40px padding; margin 0 auto; transition: transform 0.3s, background-color 0.3s ease.
- .card:hover: khaki background.
- h1::before adds "🥳 " and h1::after adds " 🥳".
- .message: font-size 1.2em; margin-bottom 20px.
- .card-links: margin-top 20px; display flex; justify-content space-around.
- .card-links a: no underline; font-size 1em; padding 10px 20px; border-radius 5px; white text; midnightblue background.
- .card-links a:visited: crimson text.
- section: margin 20px auto; max-width 600px; whitesmoke background; 20px padding; 10px border-radius; display none.
- section:hover: transform skewX(10deg).
- section:target: display block, so each section only appears when its link is clicked.

Use pseudo-classes (:hover, :visited, :target) and pseudo-elements (::before, ::after) as described, and don't use JavaScript.
