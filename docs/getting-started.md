# Getting Started with TCG Sandbox

Welcome to TCG Sandbox! This guide will help you get started creating games, building decks, and playing with others.

## Creating an Account

1. Visit [tcg-sandbox.com](https://tcg-sandbox.com)
2. Click "Sign Up" or "Log In"
3. Choose either:
   - Email/Password authentication
   - Google Sign-In (SSO)

## Your First Game

### Understanding the Creator Hub

The **Creator** is where all game design happens. Here you can:
- Create and manage your games
- Design card sets and individual cards
- Configure game rules and mechanics

### Creating a Game

1. Navigate to the **Creator** section
2. Click "Create New Game"
3. Fill in your game details:
   - **Name**: The title of your TCG
   - **Description**: What makes your game unique
   - **Banner**: Visual customization (vertical alignment, title color)
4. Define your **Game Play Data**:
   - Grid layout for the playing field
   - Number of players
   - Slot configurations (where cards can be placed)
5. Click "Create"

Your game starts as a draft and won't be playable until you mark it ready.

### Creating Card Sets

Sets are collections of cards that belong to your game.

1. Open your game in the Creator
2. Click "Add Set"
3. Configure the set:
   - **Name**: Set identifier (e.g., "Base Set", "Expansion 1")
   - **Description**: Theme or focus of this set
   - **Attributes**: Define what properties cards in this set can have

#### Defining Attributes

Attributes are the building blocks of your cards. Common examples:
- **Health**: `NUMBER` type
- **Attack**: `NUMBER` type
- **Card Text**: `STRING` type
- **Element**: Custom type with specific options

Each attribute has:
- A name
- A type (STRING, NUMBER, etc.)
- Optional constraints (min/max values, allowed options)

### Creating Cards

Once you have a set with defined attributes:

1. Navigate to the set
2. Click "Create Card"
3. Fill in card details:
   - **Name**: Card title
   - **Description**: Card lore or purpose
   - **Image**: Upload card artwork
   - **Type**: Select from game or set-defined types
   - **Attributes**: Set values for each defined attribute
4. Click "Save"

## Building Decks

Decks are personal collections of cards you'll use in games.

1. Navigate to the **Deck Builder**
2. Click "Create New Deck"
3. Choose the game your deck is for
4. Name your deck
5. Add cards:
   - Browse available cards by set
   - Click on cards to add them to your deck
   - Set quantities for each card
6. Save your deck

## Playing Games

### Joining a Lobby

1. Navigate to the **Play** section
2. Browse available game lobbies
3. Click "Join" on an open lobby

### Creating a Lobby

1. Click "Create Lobby"
2. Select which game to play
3. Configure lobby settings:
   - Public or private
   - Number of players
4. Wait for other players to join
5. Start the game when ready

### During Gameplay

Gameplay mechanics depend on the specific game you're playing. The creator of the game defines:
- How cards interact
- Win/loss conditions
- Turn structure
- Special rules and mechanics

Follow the on-screen instructions and game rules for the specific TCG you're playing.

## Tips for Success

### For Game Creators

- **Start simple**: Create a small, focused game before building something complex
- **Test thoroughly**: Play your game before marking it as playable
- **Iterate**: Use player feedback to improve your game over time
- **Document your rules**: Clear rules help players enjoy your game

### For Players

- **Read the rules**: Each game has unique mechanics
- **Experiment with decks**: Try different strategies and card combinations
- **Be patient**: Games may have bugs or balance issues as they're refined
- **Give feedback**: Help creators improve by reporting issues or suggestions

## Next Steps

- Explore [Core Concepts](concepts.md) to understand the platform in depth
- Check out the [FAQ](faq.md) for common questions
- Browse the [API Documentation](https://api.tcg-sandbox.com/docs) if you're interested in technical details

## Need Help?

If you run into issues or have questions:
- Check the [FAQ](faq.md)
- [Ask a question](https://github.com/bradlet/tcg-sandbox-community/issues/new?template=question.yml) on GitHub
- [Report bugs](https://github.com/bradlet/tcg-sandbox-community/issues/new?template=bug_report.yml) you encounter

Happy gaming! 🎮
