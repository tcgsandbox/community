# Frequently Asked Questions

## General Questions

### What is TCG Sandbox?

TCG Sandbox is a platform for creating, sharing, and playing custom Trading Card Games online. It provides tools for game design, deck building, and real-time multiplayer gameplay.

### Is TCG Sandbox free to use?

Pricing information will be available as the platform develops. The goal is to offer a free tier with optional premium features for subscribers.

### Can I really create my own card game?

Yes! You have full control over:
- Game rules and mechanics
- Card sets and individual cards
- Card attributes and types
- Visual styling
- Lore and story creation

### Do I own the cards I collect?

TCG Sandbox does not currently implement card ownership, trading, or NFT mechanics. The platform focuses on game creation and gameplay rather than collection economics.

Blockchain based ownership and physical card creation can be supported given enough community interest: add and contribute to existing feature requests now!

### Can I play games made by other users?

Yes! Once a game creator marks their game as "playable", anyone can join lobbies and play.

## Game Creation

### How do I make my game playable?

1. Create your game with complete rules
2. Design at least one set with cards
3. Test the game thoroughly
4. Toggle the "playable" flag in your game settings

### Can I update my game after publishing it?

Yes, you can continue to update:
- Game description and styling
- Game rules and mechanics
- Add new sets and cards

Be mindful that changes may affect existing decks and ongoing games.

### What's the difference between game-level and set-level attributes?

- **Game-level attributes**: Available to ALL cards in your game (e.g., "Attack", "Health")
- **Set-level attributes**: Only available to cards in that specific set (e.g., "Special Ability" in an expansion)

This allows you to add new mechanics in expansions without changing old cards.

### How many cards can I create?

There are no hard limits on the number of games, sets, or cards you can create. However, practical limits may be introduced as the platform scales.

### Can I import cards from existing TCGs?

No. You must create original content. Importing copyrighted cards from existing games (Magic: The Gathering, Pokémon, etc.) is not permitted.

### Can I use AI to generate card images?

The platform doesn't provide image generation tools, but you can upload any images you have rights to use. Ensure you have permission for any artwork you use (which you typically do, if generating custom images that respect IP rights using an LLM like ChatGPT).

## Deck Building

### Can my deck include cards from multiple sets?

Yes! Decks can include cards from any sets within the same game.

### Are there deck size restrictions?

Deck building rules are defined by each game's creator. Some games may have minimum/maximum card limits, while others are flexible.

### Can I share my deck with others?

Deck sharing features may be added in the future. Currently, decks are personal collections.

### What happens if a card in my deck gets changed?

If a game creator updates a card, those changes will reflect in your deck. This is similar to card errata in physical TCGs.

## Gameplay

### How does multiplayer work?

Players join lobbies, and gameplay happens in real-time through WebSocket connections. The game's creator defines turn structure and win conditions.

### Can I play solo?

Solo play depends on the specific game. Some games may support single-player modes if designed that way by the creator.

### What if someone disconnects during a game?

Disconnection handling depends on the game implementation. Lobbies have a 1-week TTL and will auto-cleanup inactive sessions.

### Can I spectate games?

Spectator features are not currently available but may be added in the future.

## Technical Questions

### Which browsers are supported?

Modern versions of:
- Google Chrome
- Firefox
- Safari
- Edge

### Is there a mobile app?

There is no dedicated mobile app yet. The web app works on mobile browsers, though the experience is optimized for desktop.

### Can I use the API?

API documentation is available at [api.tcg-sandbox.com/docs](https://api.tcg-sandbox.com/docs). However, public API access may be restricted depending on your use case.

### Is the code open source?

No, TCG Sandbox is a closed-source project. However, community feedback and feature suggestions are welcome through [GitHub issues](https://github.com/bradlet/tcg-sandbox-community/issues).

## Account & Privacy

### How is my data stored?

User data is stored securely in Google Cloud Firestore. Authentication is handled through Firebase Auth.

### Can I delete my account?

Account deletion features will be available. Contact the maintainer if you need immediate account deletion.

### What authentication methods are supported?

- Email/Password
- Google Sign-In (SSO)

Additional authentication providers may be added in the future.

## Contributing & Community

### How can I contribute?

While the codebase is closed-source, you can contribute by:
- Reporting bugs
- Suggesting features
- Participating in discussions
- Creating great games on the platform
- Providing feedback on new features

### Why isn't the code open source?

TCG Sandbox is a personal passion project. Keeping it closed-source allows for faster, secure development and experimentation without the overhead of managing external contributions. 

### Will it ever be open source?

There are plans to open source parts of the project in the future, so that game creators could implement better built-in support for their game's rules instead of relying on having their users understand how to represent those rule behaviors on the platform.

### How can I report security issues?

Please do not publicly disclose security vulnerabilities. Contact the maintainer directly at `mail@bradlet.com`.

## Troubleshooting

### The app won't load

Try these steps:
1. Refresh the page (Ctrl+R or Cmd+R)
2. Clear your browser cache
3. Try a different browser
4. Check if [tcg-sandbox.com](https://tcg-sandbox.com) is accessible

If problems persist, [report an issue](https://github.com/bradlet/tcg-sandbox-community/issues/new?template=bug_report.yml).

### I can't create a card

Ensure:
- You've defined attributes in your set before creating cards
- All required fields are filled
- Your session hasn't expired (try refreshing)

### My game lobby won't start

Check:
- All required players have joined
- You have selected a valid deck
- The game is marked as "playable"

### Cards aren't displaying correctly

This could be due to:
- Image upload issues
- Browser caching (try hard refresh: Ctrl+Shift+R)
- Rendering bugs (please report!)

## Still Have Questions?

- [Ask a question](https://github.com/bradlet/tcg-sandbox-community/issues/new?template=question.yml) on GitHub
- Check the [Getting Started](getting-started.md) guide
- Review [Core Concepts](concepts.md)
- Browse [existing issues](https://github.com/bradlet/tcg-sandbox-community/issues) for answers
