# Listening

A cozy pixel-art village game for practising active listening, inspired by Undertale and Stardew Valley.

You've just moved to Thistlewick. Each villager is carrying something: loss, a secret about who they love, a joy so big it scares them. When they talk to you, you type a reply. If you really listened (reflecting back what they said, naming a feeling, asking an open question, staying with them instead of fixing things), they trust you more and tell you the next part of their story. As trust grows, you can share more of yourself and eventually offer an honest opinion.

## Playing

Open `index.html` in a web browser. Walk with WASD or the arrow keys, talk with E or Space, and open your journal with J. On phones, use the on-screen controls.

When the game runs as an artifact on claude.ai, Claude reads each reply, judges it, and writes what the villager says next. Anywhere else it falls back to a simple keyword check and scripted lines.

## Changing the stories

All of the story content is at the top of the script in `index.html`, in the `CHARS` object. Each villager has six beats: an opening line, four deeper reveals, and an ending. Each beat has the line they say, a line for when you come back, and a journal note.
