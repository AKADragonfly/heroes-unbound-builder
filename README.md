# Heroes Unbound Character Builder

A comprehensive web-based character creation tool for the Heroes Unbound RPG.

## 🎭 Features

### Core Character Creation
- **Primary Characteristics**: All standard characteristics with automatic cost calculation
- **Figured Characteristics**: Auto-calculated values (Stunned, Recovery, Knockout, Endurance, Defense Total)
- **Modified Characteristics**: Create characteristic variants with custom advantages and limitations
- **Defense Conversion**: Automatic Defense (O) to Defense (OtR) conversion with real-time base adjustments

### Power System
- **Complete Framework Support**:
  - Elemental Control (base framework and slots)
  - Variable Power Pool (control + pool)
  - Multiform Pool (base framework and slots)
  - Standard powers (no framework)
- **Component-Based Powers**: Multiple components per power with individual modifiers
- **Advantages & Limitations**: Full modifier system with automatic cost calculations
- **Power-Wide Limitations**: Framework-level limitations for complex builds

### Character Management
- **Situations**: Complication system for earning build points
- **Skills**: Simple point-based skill system
- **Experience Points**: Track character advancement
- **Hero vs Villain**: Different power ratio limits (119% vs 129%)

### Smart Calculations
- **Automatic Point Tracking**: Real-time build point allocation and remaining points
- **Power Ratio Validation**: Ensures characters meet ratio requirements
- **Cost Calculations**: Proper Heroes Unbound rounding and heightened point calculations
- **Build Validation**: Comprehensive error checking and warnings

### Export & Import
- **Character JSON**: Save/load complete character data
- **Build Sheet Export**: Detailed text-based character build breakdown
- **Hero Sheet Export**: Clean player-facing character sheet
- **Cross-Session Compatibility**: Load characters across different sessions

## 🚀 Getting Started

### For Players
1. **Access**: Visit the hosted website (no downloads required)
2. **Create**: Start building your character using the tabbed interface
3. **Save**: Export your character as JSON for future sessions
4. **Share**: Export build sheets for GM review or hero sheets for play

### For GMs
- Review exported build sheets for character approval
- Validate power ratios and point allocations
- Track character advancement through experience points

## 📋 Interface Guide

### Tabs Overview
- **⚡ Situations**: Add complications to earn build points
- **📊 Characteristics**: Configure primary, figured, and modified characteristics
- **🔥 Powers**: Create complex powers with frameworks and modifiers
- **🎯 Skills**: Add skills and their point costs
- **📋 Final Points**: Summary, validation, and export options

### Character Types
- **Hero**: 119% power ratio limit, 200-point starting limit
- **Villain**: 129% power ratio limit, no starting point limit

### Key Features

#### Defense (OtR) Conversion
- Automatically converts Defense (O) to Defense (OtR)
- Maintains total ordinary defense at 10 points
- Real-time base value adjustments

#### Modified Characteristics
- Create variants of base characteristics
- Add custom advantages and limitations
- Toggle application to main character values
- Detailed notes and descriptions

#### Power Frameworks
- **Elemental Control**: Base framework with reduction for slots
- **Variable Power Pool**: Control cost plus pool allocation
- **Multiform Pool**: Shape-changing power framework
- **Component Limitations**: Automatic restrictions for framework slots

## 💾 Data Management

### Saving Characters
- Export character data as JSON files
- Include all build information and metadata
- Compatible across browser sessions

### Loading Characters
- Import previously saved JSON files
- Automatic data validation and migration
- Preserves all character information

### Export Formats
- **JSON**: Complete character data for saving/loading
- **Build Sheet**: Detailed point breakdown for GM review
- **Hero Sheet**: Clean player reference with separated bonuses

## 🎲 Heroes Unbound Integration

### Accurate Calculations
- Proper Heroes Unbound point costs and multipliers
- Correct heightened point calculations
- Framework-specific cost adjustments
- Limitation and advantage applications

### Validation Rules
- Power ratio enforcement (Hero 119%, Villain 129%)
- Point allocation validation
- Framework-specific restriction checking
- Build completeness verification

### Character Advancement
- Experience point tracking
- Cumulative point totals
- Advanced character support

## 🌐 Deployment

### Netlify Hosting
This tool is designed for static hosting on platforms like Netlify:

1. Upload the HTML file to Netlify
2. Deploy as a static site
3. Share the URL with players
4. No server or database required

### Browser Compatibility
- Modern web browsers (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- Local file system access for imports/exports

## 📖 Usage Tips

### Building Characters
1. Start with **Situations** to establish build points
2. Allocate **Characteristics** based on concept
3. Create **Powers** using appropriate frameworks
4. Add **Skills** to round out the character
5. Review **Summary** for validation and export

### Power Creation
- Use frameworks for related powers (Elemental Control for themed abilities)
- Apply limitations at the component level when possible
- Use power-wide limitations for framework restrictions
- Consider advantage/limitation interactions

### Character Optimization
- Monitor power ratio throughout building
- Balance characteristics, powers, and skills
- Ensure adequate situation points for full builds
- Review validation messages before finalizing

## 🤝 Contributing

This is an open-source character builder for Heroes Unbound. Feedback and suggestions are welcome for improving the tool's functionality and user experience.

## 📄 License

## 🔗 Resources

- [Character Builder GitHub Repository](#)

---
