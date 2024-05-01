# "Building WordPress with AI Magic" Presentation Materials

This repository contains the presentation materials for the talk "Building WordPress with AI Magic" by [Nathan Onn](https://www.nathanonn.com/). The talk was originally given at Penang WordPress Meetup on 4th May 2024.

## Slides

The slides are available in PDF format. You can download them [here](slides.pdf).

## Training Docs

The sample of the training docs I used to train the AI on generating WordPress block patterns are available [here](sample_training_docs.md).

## Article

The article that accompanies this talk is available on my blog. You can read it [here](https://www.nathanonn.com/building-wordpress-with-ai-magic/).

## Prompts

### Prompt to Generate Block Pattern

```txt
The attached markdown file are examples of block patterns in WordPress block editor.

Use it as reference to create a block pattern similar to the attached layout.

[describe the layout a bit]

Please use a placeholder image for the image block.

Please wrap the block pattern codes in code block.
```

### Prompt to describe a website layout

```
Attached is a section extracted from a website. Please describe the layout only.

RULES:
- Ignore the text content.
- Simply note the presence of any images without describing them.
```

### Prompt to create training docs

```
The attached image is the layout created in WordPress block editor using the attached block pattern codes.

Can you give me the purpose of the image, the detailed description of the image and the step-by-step instructions on how to recreate it using the block pattern codes.

Here's the structure:

PURPOSE:
(the purpose of the layout)

DESCRIPTION:
(the description of the layout)

INSTRUCTION:
(the step-by-step instructions to create the block pattern)
```

## Training Docs Structure

```
# {Title of the block pattern}

## PURPOSE
{insert the purpose here}

## DESCRIPTION:
{insert the description here}

## INSTRUCTIONS:
{insert the instructions here}

## BLOCK PATTERN
{insert the block pattern codes here}

```
