# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

Dark cyan: hsl(185, 75%, 39%)
Very dark desaturated blue: hsl(229, 23%, 23%)
Dark grayish blue: hsl(227, 10%, 46%)

### Neutral

Dark gray: hsl(0, 0%, 59%)

## Typography

### Body Copy

- Font size (name and stats): 18px

### Font

- Family: [Kumbh Sans](https://fonts.google.com/specimen/Kumbh+Sans)
- Weights: 400, 700

.container{
    background: var(--Dark-gray);
    text-align: center;
    max-width: 500px;
    border-radius: 15px;
   
}

.upper{
    height: 150px;
    width: 350px;
    background: url(./images/bg-pattern-card.svg);
    background-size: cover;
    border-radius: 5%;
}

.img{
    width: 100px;
    height: 100px;
    border-radius: 50%;
    margin: -50px auto -30px auto;
    border: 5px solid hsl(0, 0%, 100%);
}

 
.card .name{
    font-size: 1.4rem;
}

.card .city{
    margin-top: 10px;
}

.card .age 
.card .city{
    font-weight: 300;
    font-size: 1.1rem;
    color: var(--Dark-gray);
}
 
.activity{
    display: block;
    font-weight: 300;
    font-size: .9rem;
    color: var(--Dark-gray);
    letter-spacing: .1rem;
}

.activity{
    padding-top: 22px;
    padding-right: 40px;
    border-top: 1px solid var(--Dark-gray);
    padding-left: 40px;
    margin-top: 23px;
    display: flex;
    align-items: center;
    justify-content: space-between;
}