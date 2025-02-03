# Rule-Based-AI-System

Building a Rules-Based AI System in Python:
Part 1: Initial Project Ideas
  1.	Medieval Fantasy Role Quiz
      a.	Description: Create a quiz that asks the user a series of questions (e.g., personality traits, preferences, or moral choices) and assigns them a medieval fantasy role based on their answers. The               roles could include knight, rogue, wizard, bard, cleric, or even more niche roles like alchemist, blacksmith, or court jester.
      b.	Rules/Heuristics:
          i.	Use weighted scoring to determine the role. For example, if the user prefers magic over physical combat, they might be assigned the role of a wizard.
          ii.	Include branching logic based on user input (e.g., "Do you prefer solving problems with wit or strength?").
          iii.	Add a fun backstory or description for each role to make it engaging.
      c.	Example Output: "Based on your answers, you are a Rogue! You thrive in the shadows, using cunning and agility to outwit your enemies."
  2.	Lit-RPG Novel Premise Generator
      a.	Description: Build a system that generates unique premises or prompts for a Lit-RPG (Literary Role-Playing Game) novel. The generator could combine elements like setting, protagonist, conflict, and           game mechanics to create compelling story ideas.
      b.	Rules/Heuristics:
          i.	Create lists of possible settings (e.g., "a floating sky fortress," "a dungeon filled with ancient traps"), protagonists (e.g., "a former soldier turned blacksmith," "a rogue AI trapped in a                  medieval world"), and conflicts (e.g., "a war between guilds," "a quest to retrieve a stolen artifact").
          ii.	Use rules to ensure logical combinations (e.g., a "rogue AI" protagonist might not fit in a "low-tech medieval village" setting).
          iii.	Add optional game mechanics (e.g., "leveling up by defeating monsters," "crafting magical items").
      c.	Example Output: "In a world where magic is powered by music, a bard with no musical talent must level up by composing epic ballads to stop a demonic invasion."
 3.	 5th Edition DnD Character Generator
      a.	Description: Develop a character generator for Dungeons & Dragons 5th Edition that creates a fully fleshed-out character, including race, class, background, abilities, and a brief backstory.
      b.	Rules/Heuristics:
          i.	Use DnD rules to assign ability scores, skills, and proficiencies based on the chosen race and class.
          ii.	Include a database of races (e.g., elf, dwarf, tiefling), classes (e.g., fighter, wizard, paladin), and backgrounds (e.g., noble, outlander, sage).
          iii.	Generate a backstory by combining traits from the character's race, class, and background (e.g., "A half-orc barbarian with a haunted past as a gladiator").
    c.	Example Output: "You are a Half-Elf Sorcerer with the Sage background. Your innate magic comes from a draconic ancestor, and you spend your days researching ancient tomes to uncover the secrets of             your lineage."
  4.	Medieval Fantasy Name Generator
    a.	Description: Create a name generator for characters, locations, or items in a medieval fantasy world. The generator could use rules to combine prefixes, suffixes, and syllables to create names that           fit specific themes (e.g., elvish, dwarven, or demonic).
    b.	Rules/Heuristics:
          i.	Use lists of thematic syllables (e.g., "El-" for elvish names, "Grim-" for dark or ominous names).
          ii.	Apply rules for name structure (e.g., elvish names might always end with "-ion" or "-ael").
          iii.	Allow the user to specify the type of name they want (e.g., "mystical," "brutal," "elegant").
    c.	Example Output: "Your elvish character's name is Elarion Duskwhisper."
Chosen Idea: Lit-RPG Novel Premise Generator
Justification: I chose this project because it was most applicable to my real world needs and fit my current interests. It also seemed adaptable to most creative writers and matched the logic that different fantasy and sci-fi genres use to generate their fictional worlds. 

Part 2: Rules/Logic for the Chosen System
The Lit-RPG Novelk Premise generator will follow these rules: 
  1.	Setting Rules
    a.	Fantasy Worlds: Dungeons, magical academies, floating cities.
        i.	Pair with heroic or magical protagonists.
        ii.	Conflicts: Wars, magical threats, ancient artifacts.
        iii.	Mechanics: Leveling, spellcasting, crafting.
    b.	Post-Apocalyptic Worlds: Wastelands, ruined cities.
        i.	Pair with scavengers or engineers.
        ii.	Conflicts: Survival, resource wars.
        iii.	Mechanics: Permadeath, crafting, survival stats.
    c.	Virtual Worlds: MMORPGs, VR realms.
        i.	Pair with gamers, AI, or programmers.
        ii.	Conflicts: Glitches, rival players, system corruption.
        iii.	Mechanics: Respawns, skill trees, player rankings.
    d.	Hybrid Worlds: Mix of fantasy and sci-fi.
        i.	Pair with cyborgs, technomancers, or hackers.
        ii.	Conflicts: Corporate espionage, rogue AI.
        iii.	Mechanics: Cybernetic upgrades, mana circuits, hacking.
  2.	Protagonist Rules
    a.	Heroic Types: Knights, warriors, paladins.
        i.	Best for fantasy or post-apocalyptic settings.
        ii.	Conflicts: Saving the world, defeating evil.
        iii.	Mechanics: Combat stats, leadership perks.
    b.	Skill-Based Types: Rogues, bards, engineers.
        i.	Best for virtual or hybrid settings.
        ii.	Conflicts: Solving puzzles, outsmarting enemies.
        iii.	Mechanics: Crafting, stealth, charisma.
    c.	Magical Types: Mages, sorcerers, summoners.
        i.	Best for fantasy or hybrid settings.
        ii.	Conflicts: Magical threats, ancient curses.
        iii.	Mechanics: Spellcasting, mana management.
    d.	Outsider Types: AI, mutants, isekai protagonists.
      i.	Best for virtual or post-apocalyptic settings.
      ii.	Conflicts: Adapting to a new world, survival.
      iii.	Mechanics: Unique abilities, system glitches.
  3.	Conflict Rules
    a.	External Threats: Wars, invasions, monsters.
      i.	Best for fantasy or post-apocalyptic settings.
      ii.	Protagonists: Heroic or skill-based.
      iii.	Mechanics: Combat, leveling, crafting.
    b.	Internal Struggles: Betrayal, moral dilemmas.
      i.	Best for virtual or hybrid settings.
      ii.	Protagonists: Outsiders or skill-based.
      iii.	Mechanics: Reputation systems, moral choices.
    c.	System-Based Issues: Glitches, corrupt systems.
      i.	Best for virtual or hybrid settings.
      ii.	Protagonists: Outsiders or magical types.
      iii.	Mechanics: Glitches, unique abilities.
    d.	Resource-Based Issues: Scarcity, competition.
      i.	Best for post-apocalyptic or fantasy settings.
      ii.	Protagonists: Skill-based or heroic.
      iii.	Mechanics: Crafting, resource management.
  4.	Game Mechanics Rules
    a.	Combat Systems: Leveling, stats, weapon mastery.
      i.	Best for fantasy or post-apocalyptic settings.
      ii.	Protagonists: Heroic or skill-based.
      iii.	Conflicts: External threats, wars.
    b.	Crafting Systems: Enchanting, building, resource management.
      i.	Best for post-apocalyptic or hybrid settings.
      ii.	Protagonists: Skill-based or outsiders.
      iii.	Conflicts: Resource-based issues, survival.
    c.	Social Systems: Reputation, guilds, alliances.
      i.	Best for virtual or fantasy settings.
      ii.	Protagonists: Skill-based or outsiders.
      iii.	Conflicts: Internal struggles, rivalries.
    d.	Unique Systems: Glitches, hybrid abilities, permadeath.
      i.	Best for virtual or hybrid settings.
      ii.	Protagonists: Outsiders or magical types.
      iii.	Conflicts: System-based issues, external threats.

     
Part 3: Rules/Logic for the Chosen System 
Sample input and output: 
"In a world of [Setting], [Protagonist] must [Conflict] by [Game Mechanics]."
Examples:
  1.	Setting: Dungeon-filled world.
      Protagonist: Farmer turned enchanter.
      Conflict: Stop a glitch causing monsters to grow stronger.
      Mechanics: Crafting magical items.
      Premise: "In a dungeon-filled world, a farmer turned enchanter must stop a glitch causing monsters to grow stronger by crafting powerful magical items."
  2.	Setting: Magical academy.
      Protagonist: Bard with no musical talent.
      Conflict: Defeat a demonic invasion.
      Mechanics: Leveling up by composing ballads.
      Premise: "At a magical academy, a bard with no musical talent must level up by composing epic ballads to defeat a demonic invasion."
  3.	Setting: Post-apocalyptic wasteland.
      Protagonist: Scavenger with a rare crafting skill.
      Conflict: Survive a war between factions.
      Mechanics: Crafting survival gear.
      Premise: "In a post-apocalyptic wasteland, a scavenger with a rare crafting skill must survive a war between factions by crafting essential survival gear."

Part 4: Reflection: 
  •	Project Overview: This project involved designing a practical, rule-based systems to create prompt for novels in the Lit-RPG genre of books. The system uses user based input conditions (E.g. setting and      game mechanics) to create a writing prompt for a literary entry.
  •	Challenges:
      o	Grammatical errors in prompt generations: Do the prompt make sense in the fill in the blank format and can we implement randomization?
      o	Uniqueness: how do we prevent consistent repeating prompts? 
  •	Comparison to machine learning:
      o	Adaptability: 
        	Machine learning models are adaptive and can change language models to suit inputs (i.e. are more adaptive.) 
      o	Advantages: 
        	Creative freedom and isolation; you’ll never run into a prompt that is based on a previously written entry in the genre. 
        	Simplicity: prompts are simple and easy to follow and allow creative interpretation. 
      o	Limitations:
        	Adaptive language: Prompts are a bit stilted and use a kind of plug-and-play model of generation. 
        	Lack Specificity: Prompts may not be specific enough to establish world rules and encourage consistency. 


