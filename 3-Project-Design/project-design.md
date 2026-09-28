# Phase 3 – Project Design

## 1. System Architecture

The LegalEase application consists of the following major components:

User
   ↓
User Interface
   ↓
Backend
   ↓
AI Model / Document Generation Logic
   ↓
Generated Legal Document
   ↓
User

## 2. System Modules

### Module 1 – User Interface
Provides input fields and document selection options.

### Module 2 – Input Processing
Collects and validates user information.

### Module 3 – Document Generation
Uses predefined templates and/or Generative AI to create the document.

### Module 4 – Output Display
Displays the generated document.

### Module 5 – Download
Allows the user to copy or download the generated document.

## 3. User Flow

1. User opens LegalEase.
2. User selects a document type.
3. User enters required details.
4. User submits the information.
5. System processes the input.
6. Document generation logic creates the document.
7. Generated document is displayed.
8. User can copy or download the document.

## 4. Data Flow

User Input
→ Validation
→ Processing
→ AI/Template Generation
→ Document
→ Display/Download

## 5. Design Goal

The main design goal is to provide a simple, clear, and easy-to-use legal document generation system.