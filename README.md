flowchart TB
  A[Board of Directors / Supervisory Authority]
  B[Director-General (DG) - DICON]
  C[Deputy Director-General / Chief Operating Officer]
  A --> B
  B --> C

  subgraph Executive Directors
    D1[Director, Administration & Human Resources]
    D2[Director, Finance & Accounts]
    D3[Director, Production / Operations]
    D4[Director, Engineering & Maintenance]
    D5[Director, Research & Development & QA]
    D6[Director, Procurement & Supply Chain]
    D7[Director, Corporate Affairs & Legal]
    D8[Director, Internal Audit & Compliance]
    D9[Director, Security & Safety]
    D10[Director, Medical & Occupational Health]
  end

  C --> D1
  C --> D2
  C --> D3
  C --> D4
  C --> D5
  C --> D6
  C --> D7
  C --> D8
  C --> D9
  C --> D10

  subgraph Production Units (under Director, Production)
    P1[Small Arms Unit]
    P2[Ammunition & Munitions Unit]
    P3[Explosives Handling & Demolition Unit]
    P4[Armoured Vehicles / Workshop Unit]
    P5[Garment / Corporate Wear Unit (DICON-SUR)]
    P6[Ordnance Stores & Packing]
  end
  D3 --> P1
  D3 --> P2
  D3 --> P3
  D3 --> P4
  D3 --> P5
  D3 --> P6

  subgraph Support Functions
    S1[Works & Services / Facilities]
    S2[Quality Control Laboratory]
    S3[Environmental, Health & Safety (EHS)]
    S4[IT & Digital Services]
    S5[Training & Apprenticeship]
  end

  D4 --> S1
  D5 --> S2
  D9 --> S3
  D1 --> S4
  D5 --> S5
