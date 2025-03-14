# Lucky Draw System

A modern and interactive lucky draw system built with Next.js and TailwindCSS. Perfect for events, giveaways, and random selections with a beautiful user interface and smooth animations.

Try it now ➡️ https://v0-running-code.vercel.app/

![Image Alt]([image_url](https://github.com/hisham86/lucky-draw/blob/f974c4b0fc1a248e65434d1ca4eb6962538b60e8/lucky.jpeg))

## Features

- 🎯 **Interactive Draw System**: Engaging animation during the draw process
- 👥 **Participant Management**: 
  - Add participants individually
  - Bulk import from text/CSV file
  - Remove participants
- 🎁 **Gift Management**:
  - Add multiple gifts
  - Automatic gift assignment to winners
- ⚙️ **Flexible Settings**:
  - Customizable number of winners
  - Option to draw multiple winners at once
- 🎨 **Modern UI/UX**:
  - Responsive design
  - Beautiful gradients and animations
  - Clean and intuitive interface
- 🔄 **Multiple Draw Modes**:
  - Draw with remaining participants
  - Start fresh draw
  - View previous winners

## Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/hisham86/lucky-draw.git
```

2. Navigate to the project directory:
```bash
cd lucky-draw
```

3. Install dependencies:
```bash
npm install
```

4. Start the development server:
```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## Usage

1. **Adding Participants**:
   - Type participant names individually and click "Add" or press Enter
   - Or upload a text file with names (one per line)

2. **Managing Gifts** (Optional):
   - Add gift names to be assigned to winners
   - If no gifts are added, winners will receive a generic "Prize" designation

3. **Drawing Winners**:
   - Set the number of winners to draw
   - Click "Start Lucky Draw"
   - Watch the animation as winners are selected
   - View results and choose to:
     - Draw again with remaining participants
     - Start a new draw

## Technologies Used

- [Next.js 14](https://nextjs.org/) - React Framework
- [TailwindCSS](https://tailwindcss.com/) - Styling
- [Framer Motion](https://www.framer.com/motion/) - Animations
- [TypeScript](https://www.typescriptlang.org/) - Type Safety
- [App Router](https://nextjs.org/docs/app) - Next.js App Router

## Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

Built by Hisham - [@Solo_Level_27](https://x.com/Solo_Level_27)

## Acknowledgments

- Inspired by the need for a modern, user-friendly lucky draw system
- Built with modern web technologies for optimal performance and user experience
