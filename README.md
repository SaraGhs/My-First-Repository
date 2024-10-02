
<!-- README.md is generated from README.Rmd. Please edit that file -->

# My-First-Repository

This is my first repository.

It contains several folders with assets.

. Folder ‘images’ contains jpeg, bmp, and so on files that I need for my
documents. . Folder ‘plots’ contains images that I generate through
code, possibly for publisher.

The function ‘print’ will display the argument on the screen.

``` r
print("Hello, World!")
#> [1] "Hello, World!"
```

## Packages

As I develop my repo here are the packages that I use:

``` r
library(here) # A Simpler Way to Find Your Files
#> here() starts at C:/Users/sarag/OneDrive/Documents/GEOG.712/My-First-Project/My-First-Repository
library(tuneR) # Analysis of Music and Speech
library(usethis) # Automate Package and Project Setup
```

# what is your main research interest

My primary research interest lies in **bioinformatics**, specifically
the integration of **machine learning** techniques in analyzing
large-scale **genomic and microbiome data**. I am fascinated by how
computational tools can help unravel complex biological processes,
leading to the discovery of novel therapeutic targets. The
interdisciplinary nature of this field allows me to merge my passion for
biology and programming, and I aim to contribute towards advancing
personalized medicine.

# Favorites

## Favorite Music

1.  Perfect , Ed Sheeran
2.  We can’t be friends, Ariana Grande
3.  Illusion, Dua Lipa
4.  Blank Space, Taylor Swift
5.  Someone Like You, Adele

I can use package {tuneR} to read `mp3` files.

``` r
music_file <- readMP3(paste0(here(), "/Music/Taylor Swfit - blank space.mp3"))
```

And, I can also play them, but not if I want to knit my README, so do
not run.

    tuneR::play(music_file)

## Favorite Equation

$$ E = mc^2 $$ \## Favorite Artists

| Name              | Achievements                                                                                                                |
|-------------------|-----------------------------------------------------------------------------------------------------------------------------|
| Leonardo da Vinci | Master of both art and science, famous for Mona Lisa and The Last Supper, and his contributions to anatomy and engineering. |
| Vincent van Gogh  | Post-impressionist known for Starry Night and Sunflowers, with a bold, emotional style that influenced modern art.          |
| Pablo Picasso     | Co-founder of Cubism, renowned for Guernica and his innovations in abstraction and form, shaping 20th-century modernism     |
| Frida Kahlo       | Iconic for her personal self-portraits and her impact on feminist and indigenous representation, as seen in The Two Fridas  |
| Michelangelo      | Renaissance master known for the David sculpture and the Sistine Chapel ceiling, revolutionizing both art and architecture  |

# Images

``` r
knitr::include_graphics(paste0(here(), "/Images/OIP.jpeg"))
```

![](Images/OIP.jpeg)<!-- --> - My_First_Repository/ - README.Rmd -
Music/ - Favorite musics - Images/ - OIP.jpeg

``` r
summary(cars)
#>      speed           dist       
#>  Min.   : 4.0   Min.   :  2.00  
#>  1st Qu.:12.0   1st Qu.: 26.00  
#>  Median :15.0   Median : 36.00  
#>  Mean   :15.4   Mean   : 42.98  
#>  3rd Qu.:19.0   3rd Qu.: 56.00  
#>  Max.   :25.0   Max.   :120.00
```
