---
jupytext:
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.10.3
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# Literate Programming

Literate programming is a concept first expounded by Donald E. Knuth in which a computer program is given an explanation of its logic in a natural (human) language, such as English, interspersed with fragments of source code which can be interpreted as or compiled to an executable form. 

Knuth as a mathematician and computer scientist, wanted to have a technical/theory document that could also be run as a piece of code. There was to be no separation between software  and the elegant prose of the scientific paper and no more badly-commented, cryptic code in the world. If the encouragement to adopt this approach was to increase the opportunity to read and check programs, the intent was more lofty as the following excerpt from his paper explains:

```{epigraph}
The past ten years have witnessed substantial improvements in programming methodology. This advance, carried out under the banner of “structured program- ming,” has led to programs that are more reliable and easier to comprehend; yet the results are not entirely satisfactory. My purpose in the present paper is to propose another motto that may be appropriate for the next decade, as we attempt to make further progress in the state of the art. I believe that the time is ripe for significantly better documentation of programs, and that we can best achieve this by considering programs to be works of literature. Hence, my title: *“Literate Programming.”*
  
  Let us change our traditional attitude to the construction of programs: Instead of imagining that our main task is to instruct a computer what to do, let us concentrate rather on explaining to human beings what we want a computer to do.
  
The practitioner of literate programming can be regarded as an essayist, whose main concern is with ex- position and excellence of style. Such an author, with thesaurus in hand, chooses the names of variables care- fully and explains what each variable means. He or she strives for a program that is comprehensible because its concepts have been introduced in an order that is best for human understanding, using a mixture of formal and informal methods that reınforce each other.

-- Donald E. Knuth in {cite}`knuth_literate_1984`
```

We will encourage you to adopt a literate programming approach to your work and we do this because it is actually easier to do than not. Knuth's original implementation of literate programming required a new approach to programming that was (and is) quite different from the hack-it-and-see prototype that is quick to try, annoying to go back and document when it finally works. In the `python` community, the [`jupyter`](https://jupyter.org) notebook system is a literate-programming environment that also happens to be about the easiest thing to reach for when starting a new project. 

What's more, `jupyter` is set up to work through web browsers so it gives you the same experience as a user if it is running on your machine or some remote machine in the cloud. This book is part of the `jupyter` system - most pages have code examples that you can launch and play with. In the next set of notebooks we will become familiar with this system before we return to learning how to code in python (this time being able to run examples).

```{code-cell} ipython3

```
