# Transfer Learning Documentation

This directory contains the documentation for the Transfer Learning video processing pipeline, built with [Mintlify](https://mintlify.com/).

## Documentation Structure

The documentation is organized into the following sections:

### Getting Started
- [Introduction](/introduction.mdx) - Overview of Transfer Learning
- [Quickstart](/quickstart.mdx) - Quick installation and usage guide
- [Development](/development.mdx) - Guide for developers

### CLI Commands
- [CLI Overview](/cli/overview.mdx) - Overview of all CLI commands
- [Process Video](/cli/process-video.mdx) - Process local video files
- [Generate Guide](/cli/generate-guide.mdx) - Generate guides from processed data
- [Process YouTube](/cli/process-youtube.mdx) - Process YouTube videos
- [YouTube Guide](/cli/youtube-guide.mdx) - Complete YouTube processing pipeline
- [Transcribe](/cli/transcribe.mdx) - Transcribe audio from videos
- [Analyze](/cli/analyze.mdx) - Analyze video content
- [Download](/cli/download.mdx) - Download videos from various sources
- [Utilities](/cli/utilities.mdx) - Utility commands (cleanup, stop, config)

### Advanced Usage
- [Configuration](/advanced/configuration.mdx) - Advanced configuration options
- [Monitoring](/advanced/monitoring.mdx) - Monitoring and metrics collection
- [Optimization](/advanced/optimization.mdx) - Performance optimization techniques

### API Reference
- [Introduction](/api-reference/introduction.mdx) - Introduction to the API
- Core Components documentation
- Guide Generation documentation
- Utilities documentation

## Local Development

To run the documentation locally:

1. Install Mintlify CLI:
```bash
npm i -g mintlify
```

2. Run the development server:
```bash
mintlify dev
```

3. Visit http://localhost:3000 to preview the documentation.

## Building and Deploying

The documentation is automatically built and deployed when changes are pushed to the main branch.

## Contributing

To contribute to the documentation:

1. Create a new branch for your changes
2. Make your changes to the relevant MDX files
3. Test your changes locally using `mintlify dev`
4. Submit a pull request

## Documentation Checklist

- [x] Introduction
- [x] CLI Commands Overview
- [x] Process Video Command
- [x] Generate Guide Command
- [x] Process YouTube Command
- [x] YouTube Guide Command
- [x] Transcribe Command
- [x] Analyze Command
- [x] Download Command
- [x] Utility Commands
- [x] Configuration
- [x] Monitoring
- [x] Optimization
- [x] API Reference Introduction
- [ ] Video Processor API
- [ ] Audio Transcriber API
- [ ] Content Analyzer API
- [ ] Frame Extractor API
- [ ] Guide Generator API
- [ ] Downloader API
- [ ] Validation API
- [ ] Path Utilities API
- [ ] Monitoring API
