---
title: Prasanth Ananth
description: Computer Vision, AI/ML
layout: default
---

# Warehouse inventory analytics 

<img src="/images/aims-overview.png" alt="System overview" width="750">

This is work I directed at [Sientis](https://www.sientis.ai/) (a Nokia venture). Warehouses perform inventory cycle counting manually which is slow, costly, and error-prone. 
Our autonomous drones capture images of inventory locations and upload it to the on-premise edge 
server and public cloud where the images are processed and the inventory results are presented 
to the warehouse user.

## Product identification and localization

<img src="/images/barcodes.jpg" alt="Barcode detection and OCR" width="350">

We identify the product SKU/LPN by detecting barcodes (1D, QR) and using text recognition (OCR). 
We also localize the product to the specific inventory location where it was found.

**Technologies**: Image processing, Barcode detection, Optical Character Recognition (OCR), Kubernetes

## Empty bin detection 

<img src="/images/ebd.jpg" alt="Empty bin detection" width="350">

We classify whether an inventory location (i.e., bin) in empty or non-empty using a custom-trained 
machine learning (ML) model.

**Technologies**: Supervised learning, Convolutional Neural Network (CNN), Kubernetes

## Insights

We use natural language queries to analyze trends over time and provide deeper reasoning and insights on
the inventory findings.

**Technologies**: Large Language Model (LLM), Retrieval Augmented Generation (RAG), Agents, Google Cloud

## User Interface

<div style="display: flex; justify-content: space-between;">
  <img src="/images/ui-table.PNG" alt="Table view" width="45%">
  <img src="/images/ui-images.PNG" alt="Image view" width="45%">
</div>

The UI shows the latest inventory counts, compares the data with the Warehouse Management System (WMS), 
and identifies the discrepancies. The UI also displays the images captured, so that the user 
can remotely inspect any inventory location. 

**Technologies**: Express.js, React.js, MinIO, MongoDB, Google Cloud