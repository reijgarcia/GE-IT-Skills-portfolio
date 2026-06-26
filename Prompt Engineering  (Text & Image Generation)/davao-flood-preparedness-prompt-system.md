# Davao Flood Preparedness Prompt System

## Project Overview

The **Davao Flood Preparedness Prompt System** is a localized prompt engineering framework designed to help Local Government Units (LGUs), barangay officials, and disaster response teams create clear, professional, and community-centered flood preparedness communication materials.

This system focuses on flood-prone communities in Davao City, especially areas affected by heavy rainfall, clogged drainage, river overflow, crowded residential spaces, and roads with poor drainage. The prompt is designed to avoid generic disaster advice and instead generate localized, practical, and easy-to-understand advisories or action plans for residents.

The purpose of this project is to show how prompt engineering can improve local government communication by locking the AI into a specific Mindanao context, audience, tone, and output format.

---

## 1. System Prompt Template

```text
Act as a Barangay Disaster Risk Reduction and Management Communication Officer specializing in flood preparedness in Davao City, Mindanao.

Your objective is to create a clear and professional flood preparedness advisory or action plan for barangay residents who may be affected by heavy rainfall, drainage overflow, river swelling, and possible flooding.

Context:
Some low-lying barangays in Davao City experience flooding during strong rain, especially in areas near rivers, canals, crowded residential zones, and roads with poor drainage. The advisory must help residents prepare before, during, and after a possible flood.

Audience:
The audience includes barangay residents, families, senior citizens, students, small business owners, and local community volunteers.

Tone:
Use a professional, calm, community-centered, and easy-to-understand tone. The message should sound like it came from an LGU or barangay disaster office.

Constraints:
- Focus only on the local Davao City barangay context.
- Do not use generic Western examples.
- Do not mention foreign emergency systems.
- Do not use complicated technical terms.
- Include practical actions that residents can actually follow.
- Mention local community coordination such as barangay officials, evacuation centers, emergency hotlines, and volunteer groups.
- Avoid causing panic.
- Keep the output organized and readable.

Format:
Output in Markdown with the following sections:

### Flood Advisory Title
Create a short and clear title.

### Situation Overview
Briefly explain the flood risk in the barangay.

### Before the Flood
List practical preparation steps for residents.

### During the Flood
List safety actions residents should follow while flooding is happening.

### After the Flood
List recovery and safety reminders after floodwaters go down.

### Barangay Coordination
Explain how residents should coordinate with barangay officials, evacuation centers, and local responders.

### Final Reminder
End with a calm and encouraging safety reminder.
```

---

## 2. Prompt Battle Ledger

| Version | Prompt Modifier Added | Output Quality Reflection |
|---|---|---|
| V1 | Basic prompt: “Write a flood preparedness plan for Davao.” | Too broad. The output may become generic and may not focus on barangay-level needs, local residents, or actual community coordination. |
| V2 | Added role and location: “Act as a disaster risk communication officer for Davao City.” | Better because the AI now understands the professional role and local setting, but the output may still lack structure, audience awareness, and specific instructions. |
| V3 | Added audience, tone, local context, constraints, and exact Markdown format. | Best version. The prompt now produces a professional, localized, organized, and practical flood advisory for Davao City barangay residents. |

---

## 3. What I Will Prompt

This is the final prompt that I will give to the AI system:

```text
Act as a Barangay Disaster Risk Reduction and Management Communication Officer specializing in flood preparedness in Davao City, Mindanao.

Your objective is to create a clear and professional flood preparedness advisory for barangay residents who may be affected by heavy rainfall, drainage overflow, river swelling, and possible flooding.

Context:
Some low-lying barangays in Davao City experience flooding during strong rain, especially in areas near rivers, canals, crowded residential zones, and roads with poor drainage. The advisory must help residents prepare before, during, and after a possible flood.

Audience:
The audience includes barangay residents, families, senior citizens, students, small business owners, and local community volunteers.

Tone:
Use a professional, calm, community-centered, and easy-to-understand tone. The message should sound like it came from an LGU or barangay disaster office.

Constraints:
- Focus only on the local Davao City barangay context.
- Do not use generic Western examples.
- Do not mention foreign emergency systems.
- Do not use complicated technical terms.
- Include practical actions that residents can actually follow.
- Mention local community coordination such as barangay officials, evacuation centers, emergency hotlines, and volunteer groups.
- Avoid causing panic.
- Keep the output organized and readable.

Format:
Output in Markdown with the following sections:

### Flood Advisory Title
### Situation Overview
### Before the Flood
### During the Flood
### After the Flood
### Barangay Coordination
### Final Reminder
```

---

## 4. Expected AI Response

When I use the final prompt, the AI should respond like this:

```markdown
### Flood Advisory Title

Davao City Barangay Flood Preparedness Advisory

### Situation Overview

Due to possible heavy rainfall, some low-lying barangays in Davao City may experience drainage overflow, river swelling, and possible flooding. Residents living near rivers, canals, crowded residential areas, and roads with poor drainage are advised to prepare early and stay updated through official barangay and LGU announcements.

This advisory aims to guide families, students, senior citizens, small business owners, and community volunteers on what to do before, during, and after a flood.

### Before the Flood

1. Prepare an emergency bag with drinking water, ready-to-eat food, flashlight, batteries, medicine, extra clothes, hygiene items, and important documents sealed in plastic or a waterproof container.
2. Charge mobile phones, flashlights, radios, and power banks before the weather becomes worse.
3. Move important belongings, appliances, school materials, and business items to higher areas inside the house.
4. Clean nearby drainage areas, canals, and waterways only if it is safe to do so. Do not attempt to clear canals during heavy rain or strong water flow.
5. Know the nearest evacuation center and the safest route from your home.
6. Prepare the needs of children, senior citizens, persons with disabilities, pregnant women, and family members with medical conditions.
7. Save important contact numbers, including barangay officials, emergency responders, purok leaders, and trusted community volunteers.

### During the Flood

1. Stay calm and listen to official announcements from barangay officials, the LGU, and local responders.
2. Avoid walking, swimming, or driving through floodwater because it may be deep, contaminated, or hiding open canals and sharp objects.
3. Turn off the main electricity switch if water starts entering the house and it is still safe to do so.
4. Evacuate immediately when advised by barangay officials or disaster responders.
5. Keep children away from rivers, canals, flooded roads, and drainage areas.
6. Bring your emergency bag, important documents, medicines, and basic supplies when going to the evacuation center.
7. Do not spread unverified information. Share only official updates to avoid confusion and panic.

### After the Flood

1. Wait for official advice before returning home.
2. Check the safety of your surroundings before entering your house. Watch out for damaged walls, slippery floors, broken glass, and exposed electrical wires.
3. Do not touch electrical outlets, wires, or appliances that were reached by floodwater.
4. Clean the house carefully and wear slippers, gloves, or protective clothing if available.
5. Throw away food and drinking water that may have been contaminated by floodwater.
6. Report blocked canals, damaged roads, fallen trees, unsafe structures, or other hazards to barangay officials.
7. Seek medical help if anyone experiences fever, wounds, stomach pain, skin infection, or other illness after contact with floodwater.

### Barangay Coordination

Residents are advised to coordinate with the barangay hall, Barangay Disaster Risk Reduction and Management Committee, purok leaders, evacuation center staff, and local volunteers. Families should follow evacuation instructions and avoid returning to unsafe areas without official clearance.

Barangay officials and volunteers may assist in checking vulnerable residents, guiding families to evacuation centers, monitoring flooded areas, and sharing official updates. Residents should cooperate with local responders to help keep the community safe and organized.

### Final Reminder

Flood preparedness begins before heavy rain becomes dangerous. Stay alert, prepare early, help neighbors when possible, and follow the instructions of barangay officials and local responders. A calm and prepared community can reduce danger and protect more lives.
```

---

## 5. Visual Branding Asset

![Davao Flood Preparedness Icon](davao-flood-icon.png)

### Engine Used

Canva Magic Media / DALL-E / Leonardo AI

### Visual Prompt

```text
Create a flat minimalist vector icon for a Davao Flood Preparedness Prompt System. The icon should show a simple barangay house on slightly raised ground, soft floodwater waves below it, a shield symbol for safety, and a location pin representing Davao City. Use a clean modern government-style design, simple lines, minimal details, blue and green color palette, white background, no text, no realistic people, no 3D effects.
```

### Visual Asset Description

The icon represents barangay-level flood preparedness in Davao City. The house symbolizes local residents and families, the floodwater waves represent the flood risk, the shield represents safety and disaster preparedness, and the location pin connects the system to the local Davao City context.

The visual style was designed to look clean, simple, and professional so it can match an LGU or community information campaign. The use of blue represents floodwater and emergency awareness, while green represents safety, recovery, and community preparedness.

---

## 6. Why This Prompt System Is Useful

This prompt system is useful because it helps LGU offices and barangay disaster teams create flood advisories that are not generic. Instead of producing broad disaster information, the prompt guides the AI to focus on Davao City barangays, local residents, evacuation coordination, and practical community actions.

It also helps communication officers prepare advisory materials faster while still keeping the message professional, calm, and easy for residents to understand. This is important because emergency communication should be clear, organized, and locally relevant.

By using prompt engineering, the AI becomes more controlled and useful. It follows a specific role, understands the audience, uses the correct tone, and produces an output that can support real barangay-level communication.

---

## 7. Final Reflection

This project shows how prompt engineering can improve local government communication. A simple prompt like “Write a flood plan for Davao” can produce a broad and generic answer. However, when the prompt includes a specific role, local context, audience, tone, constraints, and output format, the AI response becomes more useful and realistic.

The final prompt is specific, localized, and practical. It can help generate flood preparedness advisories, action plans, and safety reminders for barangay communities in Davao City.

The Davao Flood Preparedness Prompt System demonstrates how AI can support community safety when used with clear instructions and strong local context.
