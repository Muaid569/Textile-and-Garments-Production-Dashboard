# Textile-and-Garments-Production-Dashboard
# ThreadToGarment: Integrated Textile & Garments Production Analytics Dashboard
A dynamic, multi-stage manufacturing intelligence tool built to track end-to-end production pipelines—focusing on textile fabric loom efficiency, garments sewing line outputs, real-time defect rates, target vs. actual variances, and labor productivity benchmarks.

## 1. Project Title / Headline
ThreadToGarment: Enterprise Textile & Garments Production Analytics Dashboard An interactive, data-driven operational intelligence platform designed to monitor production lines, optimize floor efficiency, and bridge the gap between textile processing and final apparel shipment metrics.

## 2. Short Description / Purpose
The ThreadToGarment Dashboard is a high-impact Power BI analytical ecosystem designed for manufacturing directors, plant managers, and quality assurance leads in the textile and apparel sector. By integrating raw floor data from both the textile milling phase (weaving/knitting) and the garments phase (cutting/sewing/finishing), this dashboard tracks machine uptime, line configuration outputs, and rejects. This tool aims to help production facilities reduce operational bottlenecks, maximize hourly output targets, enforce strict quality metrics, and drive seamless supply chain sync from raw fabric to finished garment items.

## 3. Tech Stack
The infrastructure of this production control dashboard relies on a scalable data modeling architecture:

=> Power BI Desktop – Main authoring environment for canvas UI layout, color-coded threshold alerts, and manufacturing line-wise report configuration.

=> Power Query – The transformation engine used for reshaping daily shift-wise operator sheets, cleansing messy downtime machine logs, and parsing complex style/SKU variations.

=> DAX (Data Analysis Expressions) – Extensively used to calculate advanced manufacturing KPIs such as Overall Equipment Effectiveness (OEE), Target Achievement %, Defect Rate (DHU - Defects Per Hundred Units), and operator efficiency variances.

=> Data Modeling (Star Schema) – Relationships mapping production lines, calendar shifts, style cards, and factory floors to central transaction tables (Fabric Production and Sewing Output Logs) for smooth cross-filtering.

=> File Format – .pbix for analytical asset distribution and development layout.

## 4. Data Source
=> Source: Factory Floor Manufacturing Execution Systems (MES) and Daily Production Logs.

=> Structure: The dataset incorporates unified metrics spanning across two core operational phases:

=> Textile Phase Dimensions: Fabric types (Knit/Woven), loom numbers, RPM speeds, total meters produced, and yarn wastage allocations.

=> Garments Phase Dimensions: Sewing line IDs, style/buyer profiles, target output vs. actual pieces finished, inspected quantities, total defects found, and total operator/man-hours logged per shift.

## 5. Features / Highlights
## STEP 1 - Start with the Business Problem
The factory management faced severe visual blindspots between fabric manufacturing and final garments assembling, causing massive inventory blockages and missed shipping deadlines. Due to siloed reporting, floor supervisors could not identify in real-time which sewing lines were lagging behind daily targets, why specific machine lines suffered from recurring idle downtimes, or which fabric styles caused frequent needle breakages and defect spikes during production runs.

## STEP 2 - Define the Goal of the Dashboard
The goal of this dashboard was to deploy an end-to-end "Shop Floor Single Source of Truth" that aligns Textile Mill output directly with Garments Production lines. It focuses on driving up daily Target Attainment Rates, lowering the overall Reject/Rework Percentage, monitoring operator efficiency by shift, and ensuring that optimal fabric volume feeds smoothly into the sewing lines without sudden shortages.

## STEP 3 - Walk Through the Key Visuals
=> Operational KPI Badges: Positioned at the header for instant cross-checking, tracking Total Output (Meters/Pcs), Average Line Efficiency (%), Defect Rate (DHU), and Total Downtime Hours.

=> Line-Wise Performance Matrix: A dynamic horizontal bar chart comparing Target vs. Actual production volumes across all active sewing lines, instantly highlighting high-performing rows vs underperforming cells.

=> Hourly Production Velocity Chart: A continuous dual-axis combo chart tracking actual output vs hourly threshold benchmarks, signaling exactly which hour of the shift experienced machine breakdown or low labor concentration.

=> Defect Categories Donut Chart: An interactive visual breakdown segmenting product failures into specific categories (e.g., stitching errors, fabric stains, measurement deviations) to isolate root quality issues.

=> Style & Buyer Analysis Treemap: A multi-layered visual matrix classifying volume and margin contributions by buyer codes and apparel styles, guiding planners on product complexity.

## STEP 4 - Highlight the Insight
By leveraging cross-filtering between the Defect Categories Chart and specific Sewing Line outputs, a critical bottleneck was uncovered: certain intricate apparel styles were experiencing a 15% surge in rework delays when running on specific machine groups. The dashboard clearly proved that the issue wasn't general worker slowdown, but rather a direct mismatch between complex fabric density and machine calibration configurations—allowing engineers to run swift recalibrations immediately.

## STEP 5 - Show the Business Impact
With these continuous data updates, factory directors can transition from reactive damage control to proactive line balancing. Floor leads can re-allocate manpower to lagging sewing lines on the fly, quality teams can block defective fabric rolls before they flood the cutting rooms, and planning executives can confidently quote accurate delivery times to international buyers based on actualized line speed capabilities.

## SCREENSHORTS/DEMOS
Example:



