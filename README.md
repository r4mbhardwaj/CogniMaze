# CogniMaze 🚀

Hey there, fellow maze-crushers and code whisperers! Welcome to CogniMaze, a not-so-typical blend of brainy algorithms and wicked mazes that'll make both your neurons and GPUs buzz with excitement. On this experimental quest, we're pushing the boundaries of how virtual beings think, move, and straight-up slay challenges. It’s all about that clever AI action, with a dash of gaming fun!

## What You Need to Run This Bad Boy 🎮

Make sure your rig is equipped with:

- Unity Engine (Recommended version: 2022.3.13f1; yeah, we’re that specific!)
- Python 3.9.13 (Snake emoji goes here, but really, just get Python.)

## Set Up Like a Boss 🛠

Follow these breadcrumbs to get the ball rolling (or the agent running, we should say):

1. **Summon the Project from the Depths of the Web:**

   Go forth and clone. Bring forth every ounce of code with this charm:

   ```bash
   git clone https://github.com/r4mbhardwaj/CogniMaze.git --recurse-submodules
   ```

2. **Craft Your Code Sanctuary:**

   Migrate to the `ml/` dungeon and concoct your magical environment:

   ```bash
   cd CogniMaze/ml/
   python -m venv venv
   ```

   Awaken your newfound powers:

   On Windows:

   ```bash
   venv\Scripts\activate
   ```

   On macOS and Linux:

   ```bash
   source venv/bin/activate
   ```

3. **Empower Your Realm with All the Goodies:**

   Load up on the secret sauce – the dependencies that'll make your code fly:

   ```bash
   pip install -r requirements.txt
   ```

## Dive into the Maze like a Legend 🎩

Your arsenal is prepped, now let the games begin.

### Train Your Digital Prodigy

Hop into the `ml/` lab and turn those agents into prodigies:

```bash
cd CogniMaze/ml/
mlagents-learn --run-id=<run_name> --train
```

Give your run a name that’ll make it viral on the leaderboards.

Paused? Wanna get back into the groove? Just shout 'Resume':

```bash
mlagents-learn --run-id=<run_name> --resume
```

### Show Off Your Agents' Mad Skills

Ready
