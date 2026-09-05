# ⚽ Soccer Manager Career Mode

A production-grade football (soccer) manager career simulation game built with **React**, **Tailwind CSS**, and **Lucide Icons**. Experience advanced, realistic transfer mechanics, contract negotiations, squad management, and league simulation.

## 🎮 Features

### Core Gameplay
- **10 World-Class Clubs**: Real Madrid, Manchester City, Bayern Munich, PSG, Arsenal, Barcelona, Liverpool, Inter Milan, Bayer Leverkusen, Atletico Madrid
- **Full Realistic Rosters**: 22-25 players per team with positions, ratings, wages, contract details
- **Dynamic League Simulation**: Simulate matchdays with realistic score calculations
- **Advanced Transfer System**: 
  - Express interest in players
  - Receive and manage incoming bids
  - Player choice mechanic when multiple offers exist
  - Contract negotiations with financial transparency
- **Career Management**:
  - Player progression & potential ranges
  - Contract renewals & expirations
  - Squad rotation to manage injuries & fatigue
  - Youth academy investment & player regens
  - Manager job security & board expectations

### Dashboard & UI
- **Modern Dark-Mode Dashboard**: Sleek, responsive design
- **Tabbed Navigation**:
  - Dashboard (Overview, budget, fixtures, news)
  - Squad & Contracts (Roster management, renewals)
  - Transfer Market (Buy/sell players, bidding)
  - League Standings (Live table updates)
  - Match Center (Simulate matchdays, fitness tracking)
  - Youth Academy (Scouting, prospects)
- **Real-Time Updates**: All changes reflect dynamically without page reloads
- **Detailed Player Profiles**: Form ratings, contract details, morale indicators

### Deep Systems
- **Financial Transparency**: See exact wage impact before confirming contracts
- **Player Morale & Form**: Affects performance and transfer requests
- **Injuries & Fatigue**: Squad rotation system to manage player fitness
- **Press Conferences & News Feed**: Breaking transfer rumors and board feedback
- **Match Day 15 Expiry Warnings**: Critical alerts for expiring contracts

## 🚀 Getting Started

### Prerequisites
- Node.js 16+
- npm or yarn

### Installation

```bash
git clone https://github.com/maddoxvenable-dev/soccer-manager-career.git
cd soccer-manager-career
npm install
```

### Running the Game

```bash
npm start
```

The game will open at `http://localhost:3000`

## 📁 Project Structure

```
src/
├── components/
│   ├── Dashboard.jsx
│   ├── SquadManagement.jsx
│   ├── TransferMarket.jsx
│   ├── LeagueStandings.jsx
│   ├── MatchCenter.jsx
│   ├── YouthAcademy.jsx
│   ├── PlayerProfile.jsx
│   └── ContractNegotiation.jsx
├── data/
│   ├── clubs.js
│   ├── players.js
│   └── gameConfig.js
├── hooks/
│   ├── useGameState.js
│   ├── useTransferSystem.js
│   └── useSimulation.js
├── utils/
│   ├── matchSimulation.js
│   ├── transferLogic.js
│   ├── contractCalculations.js
│   └── playerProgression.js
├── App.jsx
└── index.css
```

## 🎯 Game Mechanics

### Transfer System
1. **Browse** available players in the transfer market
2. **Express Interest** in a player you want to buy
3. **Receive Response** with asking price from selling club
4. **Negotiate** or accept the deal
5. **Manage Bids** when other clubs bid for your players
6. **Player Choice** - if multiple bids, let the player decide

### Contract Management
- Negotiate extensions with current players
- View financial impact before confirming
- Players may refuse renewal if unhappy
- **Match Day 15 Warning**: Critical alert for expiring deals
- AI clubs can poach players if deals expire

### League Simulation
- **Simulate Matchday** to advance the season
- Realistic score calculations based on team strength
- Live table updates with Matches, Wins, Draws, Losses, GF/GA, GD, Points
- Match history feed tracking all results

### Squad Management
- View full roster by position (GK, DEF, MID, ATT)
- Track player morale, form, and fitness
- Manage injuries and fatigue through rotation
- Monitor contract status and expiration dates

### Youth Academy
- Invest money into scouting network
- Generate young talents and academy graduates
- Develop prospects into first-team players
- Track potential growth over seasons

## 🛠 Tech Stack

- **React 18**: Component-based UI
- **Tailwind CSS**: Modern, responsive styling
- **Lucide React**: Icon library
- **Local Storage**: Game state persistence
- **JavaScript ES6+**: Modern syntax and patterns

## 📊 Game State Management

The game uses React Context API for state management:
- Global game state (current club, season, budget, squad)
- Transfer system state (bids, inquiries, listed players)
- League simulation state (standings, fixtures, results)
- Player progression & morale tracking

All state changes trigger UI re-renders automatically.

## 🎨 Design Philosophy

- **Dark-Mode Modern Aesthetic**: Professional, immersive gameplay experience
- **Responsive Design**: Works seamlessly on desktop and tablet
- **Intuitive Navigation**: Clear, logical tab-based interface
- **Real-Time Feedback**: Instant visual updates for all actions
- **Financial Clarity**: Always show exact impact of financial decisions

## 📈 Career Progression

- **Board Expectations**: Set and track season goals (Top 4, Win League, etc.)
- **Performance Tracking**: Monitor position in table and financial health
- **Job Security**: Poor performance triggers warnings or termination
- **Job Market**: Apply for positions at other clubs
- **Player Development**: Watch squad improve over multiple seasons

## 🎓 Learning Resources

This project demonstrates:
- Advanced React state management patterns
- Complex UI component architecture
- Game simulation algorithms
- Financial calculation logic
- Player progression systems

## 📝 License

MIT License - feel free to use this for learning or as a foundation for your own project!

## 🤝 Contributing

Contributions are welcome! Feel free to fork, modify, and submit pull requests.

---

**Start your managerial career today!** ⚽🏆