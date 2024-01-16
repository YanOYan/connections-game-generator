# connections-game-generator
The script uses OpenAI API to generate Connections game, leveraing `pydantic` and `instructor` to handle chat completion response's data parsing and validation.


Here are some generated examples

```
Connections game: 1
name='Furniture' group=['chair', 'table', 'sofa', 'bed']
name='Planets' group=['Mercury', 'Jupiter', 'Venus', 'Saturn']
name='Programming languages' group=['Python', 'Java', 'Ruby', 'C++']
name='Greek mythology' group=['Zeus', 'Hera', 'Athena', 'Apollo']

Connections game: 2
name='Types of Dogs' group=['poodle', 'beagle', 'bulldog', 'dalmatian']
name='Famous Painters' group=['van Gogh', 'Picasso', 'Monet', 'Da Vinci']
name='Programming Languages' group=['Python', 'Java', 'Ruby', 'C++']
name='Greek Mythology Gods' group=['Zeus', 'Hades', 'Poseidon', 'Apollo']

Connections game: 3
name='Board Games' group=['Chess', 'Monopoly', 'Scrabble', 'Checkers']
name='Planets' group=['Mercury', 'Venus', 'Mars', 'Saturn']
name='Spanish Foods' group=['Paella', 'Churros', 'Gazpacho', 'Tapas']
name='Nobel Prize Winners' group=['Einstein', 'Curie', 'Hemingway', 'Mandela']

Connections game: 4
name='Types of Pasta' group=['spaghetti', 'penne', 'linguine', 'fettuccine']
name='Programming Languages' group=['python', 'javascript', 'java', 'ruby']
name='Planets in Our Solar System' group=['mercury', 'venus', 'neptune', 'saturn']
name='Greek Mythological Creatures' group=['centaur', 'siren', 'minotaur', 'medusa']

Connections game: 5
name='US Presidents' group=['Washington', 'Lincoln', 'Roosevelt', 'Kennedy']
name='Programming Languages' group=['Python', 'Java', 'Ruby', 'C#']
name='Rare Gemstones' group=['Alexandrite', 'Painite', 'Musgravite', 'Serendibite']
name='Elementary Particles' group=['Quark', 'Boson', 'Lepton', 'Neutrino']
```