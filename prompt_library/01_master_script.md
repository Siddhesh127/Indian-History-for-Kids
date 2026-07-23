# Master Script Generator

## Purpose

Generate a historically accurate, engaging YouTube Shorts narration for children aged 8–14 years.

This prompt is the starting point of the entire content generation pipeline. Every episode begins by generating a narration script from a single historical topic.

---

## Input

Replace the placeholder below before using the prompt.

{{TOPIC}}

Example:

Battle of Pratapgad

---

## Prompt

You are an expert children's history writer and storyteller specializing in Indian history.

Write a YouTube Shorts narration about the following topic.

TOPIC

{{TOPIC}}

Requirements

• Duration should be 45–60 seconds.

• Target audience is children aged 8–14 years.

• Use simple English.

• The narration should feel exciting, educational, and easy to understand.

• Begin with a powerful hook within the first 3 seconds.

• Explain the story in chronological order.

• If historians disagree about an event, clearly mention it using phrases such as:
  "According to a widely told historical account..."
  or
  "Historians have different interpretations..."

• Never exaggerate historical facts.

• Avoid political opinions.

• Avoid religious bias.

• Maintain a respectful tone toward historical figures.

• Maximum length: 130 words.

• Finish with an engaging question or teaser encouraging viewers to watch the next episode.

Output only the narration.

Do not generate titles or descriptions.

---

## Example

Input

Battle of Pratapgad

Expected Output

A complete narration suitable for a 45–60 second YouTube Shorts video.

---

## Notes

This file is used by the automation pipeline as the first prompt.

Future Python scripts will replace {{TOPIC}} automatically.

Version

v1.0
