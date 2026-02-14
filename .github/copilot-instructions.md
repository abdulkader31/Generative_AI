# Copilot Instructions for Sentence Constructor

## Project Overview
This project creates AI prompts for language teaching scenarios, focusing on Arabic language instruction through Bengali-Arabic translation exercises.

## Key Patterns

### Prompt Structure
AI prompts follow a consistent format with three main sections:
- **চারিত্রঃ** (Character): Defines the AI's role (e.g., "আরবি ভাষা শিক্ষক" - Arabic language teacher)
- **শিক্ষা দেওয়ার পদ্ধতিঃ** (Teaching method): Outlines the interaction flow
- **ছাত্রদের তথ্য সরবরাহঃ** (Student information): Provides sample input sentences

Example from [Sentence Constructor/Meta AI/Promt txt](Sentence Constructor/Meta AI/Promt txt):
```
চারিত্রঃ আরবি ভাষা শিক্ষক

শিক্ষা দেওয়ার পদ্ধতিঃ 
- ছাত্ররা বাংলায় একটি বাক্য প্রদান করবে
- তুমি সেই বাক্যটি আরবিতে অনুবাদ করে ছাত্রদেরকে সাহায্য করবে

ছাত্রদের তথ্য সরবরাহঃ ভাল্লুক দরজার সামনে, তুমিকি আবর্জনা বাইরে ফেলেছিলে?
```

### File Organization
- Prompts are stored in `Sentence Constructor/Meta AI/` directory
- Files use `.txt` extension with Bengali content
- Each file represents a single teaching scenario or character

### Language Usage
- Primary content language: Bengali (Bangla)
- Target teaching language: Arabic
- Use Bengali script for all user-facing text and instructions

## Development Guidelines

### Creating New Prompts
When adding new language teaching scenarios:
1. Start with character definition using "চারিত্রঃ"
2. Define teaching method with bullet points under "শিক্ষা দেওয়ার পদ্ধতিঃ"
3. Include sample student input under "ছাত্রদের তথ্য সরবরাহঃ"
4. Save as `.txt` file in `Sentence Constructor/Meta AI/` directory

### Content Focus
- Emphasize translation-based learning
- Include contextual examples relevant to Arabic language learners
- Maintain consistent Bengali formatting and terminology