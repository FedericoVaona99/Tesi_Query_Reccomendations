# Knowledge-Augmented LLMs for Personalized Query Suggestion

This repository contains the implementation of a **K-LaMP-inspired framework** for **personalized contextual query suggestion**,  
developed as part of my MSc thesis in Data Science (University of Verona).  

The project re-implements the ideas from the paper *"Knowledge-Augmented Large Language Models for Personalized Contextual Query Suggestion"*  
and extends them by integrating **ORCID profiles** and **user attributes** (profession, nationality, personal interests)  
into the entity-centric knowledge store.

---

## 📑 Workflow

1. **Data Loading**: POI dataset, descriptions, and user profiles.  
2. **Memory Stream Construction**: logs queries, POI views, and ORCID keywords.  
3. **Entity Store Construction**: aggregates entities with counts and timestamps.  
4. **User & Session Modeling**: captures session context from recent interactions.  
5. **Prompt Building (K-LaMP style)**: original vs. enhanced with ORCID integration.  
6. **Gemini API Integration**: generates next-query suggestions under different strategies.  

---