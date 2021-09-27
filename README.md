# Deck of cards
> nbdev deck example


## Install

`pip install deck_of_cards`

## How to use

```python
card = Card(suit=3, rank=10)
print(card)
deck = Deck()
print(card in deck.cards)
deck.remove_card(card)
print(card in deck.cards)
```

    10 of Spades
    True
    False

