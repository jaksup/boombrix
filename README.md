# BOOMBRIX — IoT Tree Health Monitoring for Cities

> Startup in Residence Amsterdam · 2018–2019  
> Co-founders: Jakub Supera & Noelle Teh

---

## The Problem

Amsterdam manages **1,000,000+ trees**. Around 50% suffer from moisture stress during dry periods. Monitoring tree health traditionally relies on expensive arborists (€40–50/hr) and manual inspection — neither scalable nor timely. Satellite imagery alone can't capture soil-level conditions.

## Our Solution

BOOMBRIX combined ground-level IoT sensors with satellite NDVI data to give municipalities precise, real-time information on which trees need watering and when.

**How it worked:**
- Underground soil moisture sensors (Arduino-based units with GSM transmission) installed within the first 500mm of soil
- Sensor data correlated with Sentinel satellite NDVI indices to build a ground-truth model
- Dashboard providing actionable recommendations per tree

## Hardware

- 10 custom Arduino units with GSM connectivity
- Battery-powered, minimal surface disturbance during installation
- Tested across different soil conditions and tree pit designs

## Pilot Results

**Location:** Rapenburgerstraat, Amsterdam  
**Scale:** 9 trees · 8 weeks

Key findings:
- Observable differences in soil moisture even at street-level granularity
- Measurable differences between tree pit design types (-5cm/-10cm vs -20cm soil depth)
- Ground sensor data successfully complemented satellite NDVI readings

## Business Outcome

- Selected for **Startup in Residence Amsterdam** after competitive pitch process
- Presented at **SiRA Grand Final** (November 2019)
- Signed **framework agreement with the City of Amsterdam**
- Case owner: Jaike Bijleveld, Senior Advisor Asset Management Green, Gemeente Amsterdam

## Journey

University entrepreneurship module → internal pitch → SiRA application → hardware iterations → pilot → Demo Day → framework agreement

---

## Files

| File | Description |
|------|-------------|
| `Boombrix PITCH Startup in Residence 8_04_19.pptx` | Original pitch deck for SiRA selection |
| `SiRA Grand Final.pptx` | Final presentation with pilot results |
| `191219_Pilot Report_FINAL.docx` | Full pilot report |

---

*"Not all conditions are possible to check via satellite even if already existing technology provides accurate data on tree development."*  
— ir. Joop Spiker, Wageningen Environmental Research
