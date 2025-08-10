# Spec Template

A comprehensive template for writing application specifications and technical documentation.

## 🚀 Quick Start

### Option 1: Copy Templates to Your Project
```bash
# Copy the templates folder to your project root
cp -r templates/ your-project-name/
cd your-project-name
```

### Option 2: Use as Reference
Browse the `templates/` folder to see all available templates and copy individual files as needed.

## 📋 Template Structure

All templates are located in the `templates/` folder:

```
templates/
├── README.md              # Main index with links to all components
├── REQUIREMENTS.md        # Requirements template
├── TODO.md                # Project tracking and milestones
├── INVESTIGATION.md       # Research and pre-work documentation
├── DESIGN.md              # System design and architecture
├── .agent                 # Agent guidance for consistent support
├── .gitignore             # Git ignore file for common files
└── decisions/             # Decisions
    ├── 0000-template.md   # Decision template
    └── 0001-example-decision.md # Example decision
```

## 📁 Table of Contents

### Core Documents
- **[templates/REQUIREMENTS.md](templates/REQUIREMENTS.md)** - Requirements
- **[templates/TODO.md](templates/TODO.md)** - Project tracking and milestones
- **[templates/DESIGN.md](templates/DESIGN.md)** - System design and architecture

### Research & Investigation
- **[templates/INVESTIGATION.md](templates/INVESTIGATION.md)** - Research, analysis, and pre-work documentation

### Decisions
- **[templates/decisions/](templates/decisions/)** - Decisions directory
  - **[templates/decisions/0000-template.md](templates/decisions/0000-template.md)** - Decision template
  - **[templates/decisions/0001-example-decision.md](templates/decisions/0001-example-decision.md)** - Example decision

### Cursor Rules
- **[.cursor/rules/spec-process.mdc](.cursor/rules/spec-process.mdc)** - Cursor rules for spec template assistance

## 🎯 Getting Started

1. **Copy the templates**: `cp -r templates/ your-project-name/`
2. **Start with the TODO**: Review `TODO.md` to understand the project phases
3. **Write the Requirements**: Begin with `REQUIREMENTS.md` to define what you're building
4. **Conduct Research**: Use `INVESTIGATION.md` to document your research and analysis
5. **Design the System**: Work through `DESIGN.md` to create your system design
6. **Document Decisions**: Create decisions in the `decisions/` directory for key architectural choices

## 📝 Usage Guidelines

### When to Use This Template
- New application development
- Major system redesigns
- Complex feature implementations
- Technical architecture planning

### Workflow
1. **Discovery Phase**: Fill out REQUIREMENTS and conduct initial research
2. **Design Phase**: Create system design and document architectural decisions
3. **Implementation Phase**: Build according to the design
4. **Documentation Phase**: Update documentation based on implementation learnings

### Best Practices
- Keep documents up to date as the project evolves
- Create decisions for all significant architectural choices
- Use clear, concise language in all documents
- Include diagrams and visual aids where helpful
- Reference external resources and research in investigation docs

### Cursor Integration
This template includes Cursor rules that provide intelligent assistance when working with specifications. The rules help with:
- Phase-specific guidance and best practices
- Quality standards and review processes
- Common assistance patterns and workflows
- Communication guidelines for effective collaboration

## 🔧 Customization

### Modifying Templates
Feel free to customize the templates to fit your organization's needs:
- Update branding and company information
- Add or remove sections based on your requirements
- Modify the workflow to match your development process
- Adjust the decision template to match your decision-making process

### Adding New Templates
To add new templates:
1. Create your new template file in the `templates/` folder
2. Update this README.md to include the new template
3. Consider updating the `.agent` file if the new template requires special guidance

## 🤝 Contributing

### Template Improvements
If you have suggestions for improving the templates:
1. Fork this repository
2. Make your improvements
3. Submit a pull request with a clear description of changes

### Sharing Best Practices
Consider sharing:
- Additional template examples
- Industry-specific adaptations
- Workflow improvements
- Tool integrations

## 📚 Additional Resources

### Documentation Standards
- [IEEE Software Requirements Specification](https://standards.ieee.org/standard/830-1998.html)
- [ISO/IEC/IEEE 29148](https://www.iso.org/standard/45171.html)
- [Agile Requirements Engineering](https://www.agilealliance.org/)

### Decisions
 

### System Design Resources
- [System Design Primer](https://github.com/donnemartin/system-design-primer)
- [Clean Architecture](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)
- [Domain-Driven Design](https://martinfowler.com/bliki/DomainDrivenDesign.html)

## 📄 License

This template is provided as-is for educational and professional use. Feel free to adapt and modify for your projects.

---

**Happy Spec Writing! 🎉** 