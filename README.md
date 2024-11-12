# Mermaid Mindmap Styling Examples

## Basic Mindmap

```mermaid
mindmap
    root((Central Topic))
        Topic A
        Topic B
            Subtopic B1
            Subtopic B2
        Topic C
```

## Circle Nodes

```mermaid
mindmap
    root((Main))
        ((Topic 1))
            ((Subtopic 1.1))
            ((Subtopic 1.2))
        ((Topic 2))
            ((Subtopic 2.1))
            ((Subtopic 2.2))
```

## Square Nodes

```mermaid
mindmap
    root((Main))
        [Topic 1]
            [Subtopic 1.1]
            [Subtopic 1.2]
        [Topic 2]
            [Subtopic 2.1]
            [Subtopic 2.2]
```

## Mixed Node Types

```mermaid
mindmap
    root((Main))
        [Square Topic]
            Subtopic 1
            Subtopic 2
        (Round Topic)
            Subtopic 3
            Subtopic 4
```

## Deep Hierarchy

```mermaid
mindmap
    root((Main))
        Branch 1
            Level 2
                Level 3
                    Level 4
                        Level 5
        Branch 2
            Level 2
                Level 3
```

## With Emojis

```mermaid
mindmap
    root((🎯 Goals))
        🚀 Launch
            📅 Timeline
            ✨ Features
        💡 Ideas
            📱 Mobile
            🌐 Web
```

## Wide Structure

```mermaid
mindmap
    root((Central))
        Branch 1
        Branch 2
        Branch 3
        Branch 4
        Branch 5
        Branch 6
```

## Development Flow

```mermaid
mindmap
    root((Project))
        Planning
            Requirements
            Design
        Development
            Frontend
            Backend
        Testing
            Unit Tests
            Integration
        Deployment
            Staging
            Production
```

## Technology Stack

```mermaid
mindmap
    root((Stack))
        Frontend
            HTML
            CSS
            JavaScript
        Backend
            Python
            Node.js
            Go
        Database
            SQL
            NoSQL
```

## Project Timeline

```mermaid
mindmap
    root((2024))
        Q1
            Planning
            Setup
        Q2
            Development
            Testing
        Q3
            Launch
            Marketing
        Q4
            Scaling
            Optimization
```

```

These examples all work reliably on GitHub as they use only the core supported features:
1. Basic node types: `(())`, `[]`, `()`
2. Plain text nodes (no brackets)
3. Emoji support
4. Hierarchical structures
5. Multiple branches
6. Deep nesting

Note that GitHub's Mermaid implementation doesn't support:
- Custom colors
- Themes
- CSS classes
- Custom fonts
- Layout direction control
- Icons (other than emojis)
- Advanced node shapes like `{{}}` or `>>`

Would you like me to show more examples of working combinations?
```

# Astound Project Development Flow

```mermaid
stateDiagram-v2
   [*] --> PlaywrightTemplate
   PlaywrightTemplate --> AstoundScraping: Add Astound Logic

   AstoundScraping --> OpenTelemetry: Add Monitoring
   OpenTelemetry --> OTHell: Code Gets Messy

   OTHell --> AstoundBranch: Back to Basics
   AstoundBranch --> UnitTests: Add Tests

   UnitTests --> [*]: Project Complete

   note right of OpenTelemetry
       OT code starts to overshadow
       core scraping logic
   end note

   note left of AstoundBranch
       Simplified branch focusing
       on core functionality
   end note
```
