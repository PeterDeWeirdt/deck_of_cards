# Deck of Cards
> A deck of cards


## Install

After cloning this repository:

pip install -e .

## How to use

Playing cards in python!

```python
from deck_of_cards.deck import Deck
d = Deck()
print(f'Number of playing cards in the deck: {len(d.cards)}')
```

    Number of playing cards in the deck: 52


```python
card = d.pop_card()
print(card)
```

    Queen of Spades

