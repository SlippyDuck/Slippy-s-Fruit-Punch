# Slippy's Fruit Punch

Its a slot machine. Click spin and hope you win money. Made by Lim.

## What is this?
its a website with a java backend. the java does the math so you cant cheat easily hopefully.

## How to make start?

**Using Intellij**

1. extract the file
2. Open IntelliJ IDEA.
  Open the Project
  Select File > Open and navigate to your project folder.
3. Configure the Project SDK
  Go to File > Project Structure > Project.
  Ensure a Java SDK (JDK) is selected (JDK 11 or higher is recommended). If you don't have one, click "Add SDK" to download one.
4. Set Up the Run Configuration (Open the File as a Project)
  Right-click on Main.java in the Project view.
  Select Run 'Main.main()'.
  IntelliJ will compile the code and start the server. You should see SLOT MACHINE SYSTEM STARTING UP... in the console.
5. View the program
  Open your browser and go to http://localhost:3000.
  The Java server will serve your index.html and style.css files directly.

if you have npm just do this:
`npm run dev`

It runs the java command `javac Main.java \&\& java Main`. It starts on port 3000. Go to localhost:3000 in your browser.

## files
- Main.java: the brain, it does the spins.
- index.html: the buttons and stuff.
- style.css: makes it look nice.

## rules
- 3 of a kind = Jackpot (50x your bet)
- 2 of a kind = Pair (2x your bet)
- Everything else = You lose your bet.

### Symbols & Rarity
The machine is now balanced so the house has a slight edge.
- 7️⃣ **Jackpot** (0.1%) - 50x Payout
- 💎 **Epic** (1.4%) - 50x Payout
- 🔔 **Rare** (3.5%) - 50x Payout
- 🍋 **Uncommon** (7%) - 50x Payout
- 🍒 **Common** (18%) - 50x Payout
- 🍉/🍇/🍊 **Junk** (70% combined) - These make it harder to get a match!
