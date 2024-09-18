## Annotations

This is a basic annotation, (1)
{ .annotate }

1. :man_raising_hand: I'm an annotation! I can contain `code`, __formatted
    text__, images, ... basically anything that can be expressed in Markdown.

This is a nested annotation, (1)
{ .annotate }

1. :man_raising_hand: I'm an annotation! (1)
    { .annotate }

    1. :woman_raising_hand: I'm an annotation as well!

!!! note annotate "Annotations within Admonitions (1)"

    Lorem ipsum dolor sit amet, (2) consectetur adipiscing elit. Nulla et
    euismod nulla. Curabitur feugiat, tortor non consequat finibus, justo
    purus auctor massa, nec semper lorem quam in massa.

1. :man_raising_hand: I'm an annotation!
2. :woman_raising_hand: I'm an annotation as well!

Annotations within Tabs:

=== "Tab 1"

    Lorem ipsum dolor sit amet, (1) consectetur adipiscing elit.
    { .annotate }

    1.  :man_raising_hand: I'm an annotation!

=== "Tab 2"

    Phasellus posuere in sem ut cursus (1)
    { .annotate }

    1.  :woman_raising_hand: I'm an annotation as well!
