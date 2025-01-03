# Pyramid Scheme

Pyramid Scheme ($SHARES) is the world’s first AI-controlled pyramid scheme! Powered by advanced GPT-4 Turbo, this revolutionary bot automates the process of building and maintaining a self-sustaining network of participants. Designed for those daring enough to experiment with innovation and risk, Pyramid Scheme uses AI to maximize engagement and "returns" in a gamified financial system.

Follow Pyramid Scheme Sample Usage on Twitter: [@aiPyramidScheme](https://x.com/aiPyramidScheme)

## Features

- Automated Scaling: Dynamically recruits participants using social media trends and engagement metrics.
- Gamified Contributions: Tracks contributions in real time and displays levels of the "pyramid" in an engaging visual format.
- AI Strategy Optimization: Adapts to market conditions to maintain momentum and intrigue.
- $SHARES Token Integration: Seamlessly integrates with the $SHARES token for tracking contributions and redistributions.

## Getting Started

To get started with the Pyramid Scheme, follow these steps:

1. Clone this repository to your local machine.
2. Install the necessary dependencies using •npm or •yarn.
3. Set up your Twitter developer account and obtain API keys.
4. Configure the bot with your Twitter API keys and other credentials by creating a `.env` file and filling it with variables from `.env.example`.
5. Link the $SHARES token and configure initial contribution thresholds.
6. Launch the bot application and let the pyramid grow!

### Modifying Prompts

To modify the prompts used by Pyramid Scheme, follow these steps:

1. Open the `pyramid-prompts.constant.ts` file in the `src/constants` directory.
2. Locate the `pyramidPrompts` array, which contains the prompts for various schemes and strategies.
3. Each object in the `pyramidPrompts` array represents a prompt for a specific scheme tier.
4. Update the `prompt` property of each object to customize the strategy for the pyramid.
5. Add new schemes or adjust tiers to fit your concept.
6. Save your changes and restart the bot application.

## Usage

Once configured and running, Pyramid Scheme will automatically post updates and recruit participants according to its schedule. You can customize the frequency of posts by modifying the Cron schedule in the `manage-scheme.service.ts` file.

## Contributing

If you'd like to contribute to Pyramid Scheme, feel free to submit pull requests with new features, bug fixes, or enhancements. Your input is invaluable in evolving this unique concept!

## License

This project is licensed under the [MIT License](LICENSE).
