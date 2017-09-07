# Flex styling

``` display: flex; ```

Le display flex n'est hérité que par l'enfant (pas le petit-enfant).

## Direction
Flex direction correspond à la direction de l'axe du flow (horizontal ou vertical).
``` flex-direction: column; ```
``` flex-direction: column-reverse; ```

Commencer au début de l'axe (start, center, end)

## Justifying content 

``` justify-content: flex-start; ```

Centre les élements dans leur block 
```
    justify-content: space-between;
    justify-content: space-around    
```

## Align items

``` align-items: stretch; ```

``` align-items: center; // flex-start, flex-end, center... ```

## Ordering


``` 
    order: -1;
    order: 0;
```

## Grow div with content

La div va s'agrandir en fonction du contenu dedans 

``` flex-grow: 1; ```

Si on veut restreindre une sidebar par exemple:

``` flex-basis: 25%; ```


## Wrap

``` flex-wrap: wrap ```

nowrap: ne va pas casser le flux des block
wrap: ne va pas casser le contenu des block
