# ![Creatalk Logo](creatalk-white.png)

## About

**Creatalk** is an AI-powered language learning platform designed specifically for UX/UI designers who want to improve their English communication skills in professional design contexts. The tool generates realistic, context-rich conversations between designers covering various scenarios—from casual team chats and client meetings to design critiques and workshop discussions. Users can customize their learning experience by selecting conversation modes (like Brand Strategy or Design System Planning), choosing their English proficiency level (Beginner, Intermediate, or Advanced), and deciding between 2 or 3 speaker formats.

## Features

Creatalk combines cutting-edge AI technology with thoughtful UX to create an immersive learning experience. Each generated conversation includes **text-to-speech audio playback** powered by ElevenLabs with gender-matched voices, allowing learners to hear natural pronunciation and intonation. The platform extracts **key design terminology** from conversations and displays them with IPA pronunciation guides, definitions translated into 20+ languages, and individual word audio playback. Users can save favorite conversations, adjust text highlighting preferences, and switch between dark and light themes. The tool also enforces realistic paragraph lengths appropriate to each proficiency level, ensuring conversations feel authentic rather than overwhelming.

## Technology

Built with React, TypeScript, and Tailwind CSS on the frontend, Creatalk leverages Supabase (via Lovable Cloud) for authentication, database management, and serverless edge functions. Conversation generation is powered by Google's Gemini AI models through the Lovable AI Gateway, while translations and gender detection utilize specialized AI endpoints. The platform supports both authenticated users with unlimited generation access and anonymous users with a trial limit to encourage registration. All user preferences, settings, and favorite conversations are persisted to provide a seamless, personalized experience across sessions.
