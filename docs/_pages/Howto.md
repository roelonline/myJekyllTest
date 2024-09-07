---
layout: single
title: ""
permalink: /howto-openapi/
classes: wide
---

# How to Use the OpenAPI Documentation Viewer

This page allows you to visualize OpenAPI specifications using **Swagger UI**. You can either select an existing OpenAPI spec from the dropdown or paste your own JSON specification. Follow the steps below to get started.

## 1. Click on 'Visualizer' in the menu

At left side of this page there is a menu. Click on the Visualizer menu item.

## 2. Select an Existing OpenAPI Spec

At the top of the page, you'll find a dropdown menu listing pre-configured OpenAPI specifications. To view one of these specs:

1. Open the dropdown.
2. Select a specification from the list.
3. The Swagger UI will automatically load and display the selected API documentation.

## 3. Paste Your Own OpenAPI Specification

If you have your own OpenAPI spec in JSON format, you can visualize it on this page by following these steps:

1. In the provided textarea, paste your JSON-formatted OpenAPI specification.
2. Click the **Visualize** button below the textarea.
3. The Swagger UI will parse and display the API documentation based on your input.

Make sure that the JSON you paste is properly formatted. If there are errors in the JSON, you will receive an alert notifying you that the specification could not be loaded.

## 4. View the API Documentation

Once an OpenAPI spec is loaded, Swagger UI will provide a fully interactive visualization, allowing you to:

- Browse the available endpoints.
- View detailed information about each API path, including request and response structures.
- Explore the parameters, models, and available operations for each endpoint.

## Notes

- If you encounter any issues loading a spec, ensure that the JSON is valid and properly formatted.
- This page supports dynamic loading of both pre-configured and user-provided OpenAPI specifications.

Feel free to experiment with different API specs and see how the documentation is generated in real time!
