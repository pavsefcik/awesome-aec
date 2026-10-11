# Awesome AEC

A working inventory of software, platforms and tools used across architecture, engineering,
construction and the built environment — **114 entries across 15 categories**.

Machine-readable versions of the same data: **[`tools.csv`](tools.csv)** · **[`tools.json`](tools.json)**
(fields: `name`, `category`, `description`, `url`, `market`, `maturity`, `buyer`, `notes`).

Each entry follows the same shape:

> **[Name](url)**
> Description — what it does, in one line.
> **Market** — directional read on adoption across **FR**, **CH**, **DE** and **US**, plus maturity.
> **Buyer** — who actually uses it: architect · engineer · contractor · owner · BIM manager · visualization artist, etc.

Categories follow a functional grouping: design and CAD, computation and 3D, emerging design
platforms, engineering, openBIM and data, AI design workspaces, visualization (render engines
vs AI imagery, each split architecture-specific vs general-purpose), practice operations,
reality capture, coordination/CDE, sustainability, urban research and products.

> **Reading the market column.** Adoption notes are directional, not exhaustive — they vary by
> firm size, discipline and whether the work is architecture, engineering, construction or real
> estate. Maturity tags: *established → growing → emerging → experimental*.
>
> **⚠ Caveats** flag ambiguous domains, name collisions or tools that are not commercial
> products (e.g. research prototypes). Verified **October 2026**.

---

## Design & CAD

#### [Autodesk Revit](https://www.autodesk.com/products/revit/overview)
BIM software for coordinated architectural, structural and MEP design.
**Market:** Dominant in the US; very strong in CH and DE; widespread in FR, especially in large firms and multidisciplinary practices. **Established.**
**Buyer:** architects · engineers · BIM managers

#### [Graphisoft Archicad](https://www.graphisoft.com/)
Architect-focused BIM authoring and documentation tool.
**Market:** Strong in CH, DE and FR; particularly popular among architecture-led practices; meaningful but smaller US presence. **Established.**
**Buyer:** architects

#### [Autodesk AutoCAD](https://www.autodesk.com/products/autocad/overview)
Industry-standard 2D drafting and 3D CAD.
**Market:** Universal across all four markets; still foundational for documentation, engineering and legacy workflows. **Established.**
**Buyer:** architects · engineers · contractors

#### [Trimble SketchUp](https://sketchup.trimble.com/)
Fast, intuitive 3D modelling for concepts and design communication.
**Market:** Very broad adoption in all markets; especially common in early design, interiors and small practices. **Established.**
**Buyer:** architects · interior designers · contractors

#### [Vectorworks](https://www.vectorworks.net/)
CAD/BIM platform strong in architecture, landscape and entertainment.
**Market:** Strong in entertainment, landscape and architecture; notable in US and DE, with a solid European base. **Established.**
**Buyer:** architects · landscape architects · entertainment designers

#### [Allplan](https://www.allplan.com/)
BIM/CAD software with strong detailing and construction documentation.
**Market:** Particularly strong in DACH — Germany, Switzerland, Austria — with a meaningful French footprint; less common in the US. **Established.**
**Buyer:** architects · engineers · contractors

#### [BricsCAD](https://www.bricscad.com/)
Cost-effective AutoCAD-compatible CAD platform.
**Market:** Cost-conscious AutoCAD alternative; present across Europe including CH and DE, with growing but limited US adoption. **Growing.**
**Buyer:** engineers · drafters · contractors

#### [MicroStation](https://www.bentley.com/software/microstation/)
Bentley CAD/BIM platform for infrastructure and large projects.
**Market:** Strong in civil, infrastructure, rail and large public projects; notable in US, DE and CH; specialized in FR. **Established.**
**Buyer:** engineers · infrastructure owners

#### [Tekla Structures](https://www.tekla.com/products/tekla-structures)
Structural BIM for steel, concrete and fabrication detailing.
**Market:** Strong among structural engineers and fabricators in all four markets; especially established in Nordic/DACH-influenced steel and concrete workflows. **Established.**
**Buyer:** structural engineers · fabricators · detailers

#### [FreeCAD](https://www.freecad.org/)
Open-source parametric 3D CAD modeller.
**Market:** Global open-source community; useful for parametric/custom work, but limited mainstream AEC production adoption. **Growing (open source).**
**Buyer:** developers · makers · students

---


## Computational & Specialist 3D

#### [Rhino 3D](https://www.rhino3d.com/)
Precise NURBS modelling for complex geometry.
**Market:** Very strong in architecture, industrial design and fabrication across FR, CH, DE and US. **Established.**
**Buyer:** architects · industrial designers · fabricators

#### [Grasshopper](https://www.rhino3d.com/features/#grasshopper)
Visual programming for parametric and generative design; included with Rhino.
**Market:** The default computational-design environment in leading architecture and engineering practices globally. **Established.** ⚠ `grasshopper3d.com` is vendor-announced as being discontinued; the community moved to `discourse.mcneel.com`.
**Buyer:** computational designers · architects · engineers

#### [Blender](https://www.blender.org/)
Open-source 3D modelling, animation and rendering.
**Market:** Strong among visualization artists and smaller studios; increasingly used in architecture, though less embedded in BIM workflows. **Growing (open source).**
**Buyer:** visualization artists · small studios · open-source developers

#### [Cinema 4D](https://www.maxon.net/en/cinema-4d)
3D modelling and animation, popular in visualization.
**Market:** Particularly strong in German-speaking markets and motion-design/visualization studios. **Established.** Maxon is a Nemetschek subsidiary.
**Buyer:** visualization artists · motion designers

#### [Autodesk 3ds Max](https://www.autodesk.com/products/3ds-max/overview)
High-end 3D modelling, animation and rendering.
**Market:** Established in high-end architectural visualization; strong in US and Europe. **Established.**
**Buyer:** visualization artists

#### [Unreal Engine](https://www.unrealengine.com/)
Real-time 3D engine for interactive visualization and VR.
**Market:** Used by advanced visualization teams, VR/AR workflows and large firms; global adoption. **Established.** Epic Games.
**Buyer:** visualization teams · digital-twin developers

#### [Twinmotion](https://www.twinmotion.com/)
Fast real-time architectural visualization.
**Market:** Accessible real-time rendering option with broad international adoption, especially where Archicad/Revit users need fast output. **Established.** Epic Games, powered by Unreal Engine.
**Buyer:** architects · visualization generalists

#### [Autodesk Forma](https://www.autodesk.com/company/autodesk-platform/aec)
Cloud tool for early-stage site, massing and environmental design.
**Market:** Newer Autodesk platform; strongest where firms are already Autodesk-centric, including US, UK and parts of Europe. **Growing.**
**Buyer:** architects · urban planners · developers

---


## Emerging Design & AI-Native Platforms

#### [Rayon](https://www.rayon.design/)
Collaborative online CAD for architectural drawings.
**Market:** European, architecture-first; appealing to smaller studios and design-led teams in FR, CH and DE. **Emerging.**
**Buyer:** architects · small studios

#### [Snaptrude](https://www.snaptrude.com/)
Browser-based collaborative building modelling.
**Market:** Early traction with tech-forward architecture teams; strongest visibility in US and India-led international markets. **Emerging.**
**Buyer:** architects · design teams

#### [Arcol](https://arcol.io/)
Web-native architectural modelling and presentation tool.
**Market:** Early-stage, design-forward; mostly innovation teams and startups rather than mainstream production. **Emerging.**
**Buyer:** architects · concept designers

#### [Motif](https://motif.io/)
Collaborative, web-based design and documentation platform.
**Market:** Emerging platform; early adopters in US and European tech-oriented practices. **Emerging.**
**Buyer:** architects · design teams

#### [Qonic](https://www.qonic.com/)
Cloud BIM/modelling platform for collaborative building design.
**Market:** Early-stage European-origin platform; potential relevance in CH/DE/FR, but still niche. **Emerging.**
**Buyer:** BIM managers · model authors

#### [That Open Platform](https://platform.thatopen.com/)
Open-source infrastructure for openBIM apps and data.
**Market:** Global developer/open-source ecosystem; relevant wherever IFC/openBIM is prioritized, including CH, DE and FR. **Growing (open source).**
**Buyer:** developers · BIM managers

#### [Giraffe](https://www.giraffe.build/)
Cloud platform for site planning and urban design.
**Market:** More common in planning, masterplanning and proptech contexts; strongest early traction in anglophone markets. **Growing.**
**Buyer:** urban planners · developers · proptech

#### [Spacio](https://spacio.ai/)
Data-driven design and AEC workflow platform.
**Market:** Emerging; likely relevant to data-driven practices rather than broad market adoption. **Emerging.**
**Buyer:** data-driven designers · planners

#### [Hypar](https://hypar.io/)
Generative design platform for building systems and layouts.
**Market:** Specialist generative-design platform; adoption among advanced computational teams, especially in the US. **Emerging.** Pivoted away from computational design in 2024.
**Buyer:** computational designers · engineers

#### [Finch](https://www.finch3d.com/)
AI-assisted generative floorplan and layout design.
**Market:** Early-stage AI/generative design; interest from architecture firms exploring automation. **Emerging.**
**Buyer:** architects · multi-family developers

#### [Augmenta](https://www.augmenta.ai/)
AI automation for building design and engineering — starting with electrical, extending into MEP.
**Market:** Early-stage automation for building systems/design; primarily innovation-led adoption. **Emerging.** Distinct from the unrelated agritech company acquired by CNH in 2023.
**Buyer:** MEP engineers · electrical engineers

#### [Branch3D](https://www.branch3d.com/)
Real-time structural design and analysis with live carbon feedback.
**Market:** Niche/early-stage; market presence likely limited and project-specific. Incubated within StructureCraft, Vancouver. **Emerging.**
**Buyer:** structural engineers

---


## Structural & MEP Engineering

#### [ETABS](https://www.csiamerica.com/products/etabs)
Structural analysis and design of buildings.
**Market:** Strong in US and international high-rise/building engineering; used by specialized structural firms in Europe. **Established.**
**Buyer:** structural engineers

#### [Dlubal RFEM](https://www.dlubal.com/en)
FEM structural analysis and design software.
**Market:** Very strong in DACH — especially Germany and Switzerland — and increasingly used elsewhere in Europe. **Established.**
**Buyer:** structural engineers

#### [IDEA StatiCa](https://www.ideastatica.com/)
Steel connection and structural joint design.
**Market:** Strong among structural engineers and fabricators in Europe including CH, DE and FR; growing US adoption. **Growing.**
**Buyer:** structural engineers · fabricators

#### [MagiCAD](https://www.magicad.com/)
MEP design and calculation inside BIM platforms.
**Market:** Especially established in Northern Europe and DACH; relevant where Revit-based MEP design is standardized. **Established.**
**Buyer:** MEP engineers

---


## Open BIM, Interoperability & Data

#### [Speckle](https://speckle.systems/)
Open platform for sharing and versioning AEC model data.
**Market:** Strong with computational and openBIM-oriented teams globally; growing in CH, DE, FR and US. **Growing.** ⚠ Funding figures conflict across sources (Suffolk Technologies investment, Apr 2026).
**Buyer:** computational designers · BIM managers · developers

#### [IfcOpenShell](https://ifcopenshell.org/)
Open-source toolkit for reading, writing and processing IFC.
**Market:** Global open-source standard for IFC automation; used by BIM managers and developers. **Established (open source).**
**Buyer:** developers · BIM managers

#### [Bonsai](https://bonsaibim.org/)
Open-source BIM authoring built on Blender.
**Market:** Emerging Blender-based BIM workflow; niche but relevant to openBIM communities in Europe. **Emerging (open source).**
**Buyer:** openBIM architects · Blender users

#### [xBIM Toolkit](https://github.com/xBimTeam/XbimEssentials)
.NET toolkit for building IFC/BIM applications.
**Market:** Developer-oriented; used in custom BIM solutions rather than by typical design teams. **Emerging (open source).**
**Buyer:** .NET developers


## AI Design Workspaces & Agents

#### [xFigura](https://www.xfigura.ai)
AI-powered BIM data and model intelligence tool; collaborative AI canvas with Rhino/Revit integrations.
**Market:** Early-stage; likely niche adoption. **Emerging.**
**Buyer:** architects · design teams

#### [Synaps](https://synaps.app)
AI tool that imports DXF/PDF, drafts documentation and generates floor plans.
**Market:** Early-stage/niche. **Emerging.**
**Buyer:** architects · documentation teams

#### [Arkyv](https://www.arkyv.ai)
AI platform for architectural project data and archives — BIM task automation, code/standards search with citations.
**Market:** Early-stage/niche. ⚠ `arkyv.org` is an unrelated text-world engine. **Emerging.**
**Buyer:** architects · BIM managers

#### [AIRI lab](https://airilab.com)
AI research and tools for the built environment — concept generation, cloud generative 3D, agentic workflows.
**Market:** Early-stage/niche. ⚠ Own site spells it "AIRIlab". **Emerging.**
**Buyer:** designers · innovation teams

#### [Reer](https://www.reer.co)
Agentic layer automating Rhino, Grasshopper and Revit workflows.
**Market:** Early-stage/niche. ⚠ Canonical domain is `reer.co`, not `reer.ai`. **Emerging.**
**Buyer:** computational designers · BIM managers

#### [Versur](https://versur.ai)
Composable agentic AI across Rhino and Grasshopper.
**Market:** Early-stage/niche. **Emerging.**
**Buyer:** computational designers

---


## Visualization & Rendering

#### [D5 Render](https://www.d5render.com/)
Real-time architectural rendering and visualization, with live links to Revit/SketchUp/Rhino.
**Market:** Growing challenger, with increasing adoption among younger visualization teams internationally. **Growing.**
**Buyer:** architects · visualization artists

#### [Enscape](https://www.chaos.com/enscape)
Real-time rendering plugin for Revit, Archicad, SketchUp and Rhino.
**Market:** Very strong in architecture practices across US, CH, DE and FR; common because of Revit/Archicad integration. **Established.**
**Buyer:** architects · interior designers

#### [V-Ray](https://www.chaos.com/vray)
High-end photorealistic rendering engine.
**Market:** Established globally among visualization specialists and larger firms. **Established.**
**Buyer:** visualization specialists

#### [Lumion](https://lumion.com/)
Fast architectural rendering and animation.
**Market:** Broad architectural adoption in Europe and the US; especially popular for fast external visuals. **Established.**
**Buyer:** architects · landscape architects


## AI Visualization & Imagery — Architecture-Specific
#### [Veras](https://www.evolvelab.io/veras)
AI-enhanced architectural rendering and image iteration, driven from Revit, Rhino, SketchUp, Archicad or Vectorworks.
**Market:** Early-stage AI visualization; adoption among firms experimenting with AI workflows. **Growing.**
**Buyer:** architects · visualization teams

#### [Rendair](https://rendair.ai/)
AI-generated architectural visuals and renderings from sketches, plans and models.
**Market:** Early-stage; likely strongest among smaller studios and marketing/competition workflows. **Emerging.** An AI renderer, not distributed-compute rendering.
**Buyer:** small studios · marketing teams

#### [Visoid](https://www.visoid.com/)
AI visualization for architectural concepts, preserving imported model geometry.
**Market:** Early-stage/niche. **Emerging.** $2.5M round, Aug 2026.
**Buyer:** architects · visualization teams

#### [Gendo](https://www.gendo.ai/)
AI image generation for architectural visualization — material tests, planning visuals, live client iteration.
**Market:** Early-stage/niche. **Emerging.**
**Buyer:** architects · client-facing teams

---

#### [Narva AI](https://www.narva.ai)
AI assistant/tooling for AEC workflows — renders, style transfer, video and 3D.
**Market:** Early-stage/niche. **Emerging.**
**Buyer:** architects · interior designers

#### [FORMAS.AI](https://www.formas.ai)
AI platform turning sketches into 2D visuals, 3D models and client-ready boards.
**Market:** Early-stage; market presence still forming. **Emerging.**
**Buyer:** architects · marketing & BD teams

## AI Imagery & Creative Tools — General-Purpose

#### 
*Not AEC-specific. Included because they are widely used in concept imagery, marketing and visualization workflows.*

#### [Runway](https://runway.com/)
AI video and image generation/editing and world models.
**Market:** Not AEC-specific; used for concept imagery, marketing and narrative visualization globally. **Growing.** ⚠ Video, not architectural software.
**Buyer:** marketing teams · concept designers

#### [Nano Banana](https://deepmind.google/models/gemini-image/pro/)
Google DeepMind's Gemini image generation and editing models.
**Market:** General-purpose AI imaging; not AEC-specific. **Growing.** ⚠ A model, not a product — increasingly embedded in other tools.
**Buyer:** designers · marketers

#### [Midjourney](https://www.midjourney.com/)
AI image generator for concepts and visual exploration.
**Market:** Very widely used for early concept imagery across all markets. **Established.**
**Buyer:** concept designers · architects

#### [Leonardo AI](https://leonardo.ai/)
AI image-generation platform for creative workflows.
**Market:** General creative AI; used for moodboards and concept exploration. **Growing.**
**Buyer:** designers · marketers

#### [Adobe Firefly](https://firefly.adobe.com/)
Adobe's generative AI for images and creative content.
**Market:** Broad creative-market adoption; useful for concept and marketing imagery. **Established.**
**Buyer:** designers · marketers

#### [Krea](https://www.krea.ai/)
AI creative tool for realtime image generation, editing and enhancement.
**Market:** Early-stage creative AI; niche in AEC. **Growing.**
**Buyer:** creative technologists

#### [Figma Weave](https://weave.figma.com/)
Node-based canvas combining many AI models for image/video/motion.
**Market:** More product/UX-oriented than AEC-specific; relevant to digital design teams. **Emerging.**
**Buyer:** digital & product designers

#### [ComfyUI](https://www.comfy.org/)
Node-based interface for building custom AI image workflows.
**Market:** Technical/creative users building custom AI pipelines; niche but powerful. **Growing (open source).**
**Buyer:** technical artists · AI pipeline builders

#### [Magnific](https://www.magnific.com/)
AI image upscaling and detail enhancement.
**Market:** Used by visualization studios globally for post-production enhancement. ⚠ Domain changed from `magnific.ai` (now a legacy portal for existing accounts); `magnifi.ai` is an unrelated company. **Growing.**
**Buyer:** visualization studios

#### [Meshy](https://www.meshy.ai/)
AI generation of 3D models and textures.
**Market:** Emerging; useful for concept massing, assets and game-like environments rather than construction documentation. **Emerging.**
**Buyer:** concept artists · game & viz teams

---


## Practice Operations & AI for AEC Firms

#### [Pirros](https://www.pirros.com)
Platform for reusing architectural details and firm knowledge.
**Market:** Emerging; relevant to architecture firms standardizing details and internal knowledge. **Emerging.**
**Buyer:** architects · BIM managers (detail libraries)

#### [Structured AI](https://getstructured.ai)
AI QA/QC agents reviewing PDF and Revit packages against firm standards.
**Market:** Early-stage/niche. **Emerging.**
**Buyer:** QA/QC leads · BIM managers

#### [Tektome](https://www.tektome.com)
AI for specifications, documents and technical content — reads drawings, models and specs against codes and client requirements.
**Market:** Early-stage; potentially relevant to specification and tender workflows. **Emerging.**
**Buyer:** specifiers · architects · contractors

#### [Freeda](https://www.freedaai.com)
AI assistant for architecture practice workflows; flags project-file risks and compliance issues.
**Market:** Early-stage/niche. ⚠ Domain is `freedaai.com`; `freeda.ai` is an unrelated menopause app. **Emerging.**
**Buyer:** architects · project leads

#### [Kinship](https://kinship.io/)
Revit content management: search, load and track families; AI platform for AEC operations and knowledge.
**Market:** Early-stage/niche. Claims 300+ firms. **Growing.**
**Buyer:** BIM managers · Revit content managers

#### [Orkestra](https://www.orkestra.online/)
Deploys, versions and governs Dynamo/Grasshopper scripts across Revit, Rhino and Civil 3D.
**Market:** Emerging; likely relevant to project operations and data workflows. **Emerging.**
**Buyer:** BIM managers · computational designers

#### [OOTI](https://www.ooti.co/)
Practice management for architecture firms: projects, time, fees and staffing.
**Market:** French-origin practice-management platform; strongest natural fit in FR, with potential in other European markets. **Established (FR).** 900+ firms.
**Buyer:** principals · practice managers (architecture firms)

#### [JOOC](https://www.jooc.ai/)
AI copilot analysing tender DCE documents and drafting bid responses.
**Market:** Early-stage/niche. ⚠ Canonical domain is `jooc.ai`. **Emerging (FR).**
**Buyer:** bid managers · contractors · architects

#### [Raygister](https://www.raygister.com/)
Structures descriptifs and DPGF so parties can compare tenders and quotes.
**Market:** Early-stage/niche. **Emerging (FR).**
**Buyer:** cost consultants · quantity surveyors · contractors

---


## Reality Capture & Digital Twins

#### [Matterport](https://matterport.com/)
3D capture and digital twins for spaces and buildings.
**Market:** Broad adoption in real estate, facilities and construction documentation across all four markets. **Established.**
**Buyer:** owners · facility managers · real-estate marketers

#### [Agisoft Metashape](https://www.agisoft.com/)
Professional photogrammetry from photos and drone imagery.
**Market:** Strong among surveyors, heritage, drone and visualization specialists globally. **Established.**
**Buyer:** surveyors · heritage specialists · drone operators

#### [RealityScan](https://www.realityscan.com/)
Mobile photogrammetry app for 3D capture (rebranded RealityCapture).
**Market:** Accessible capture tool; adoption among smaller teams and field users. **Growing.** Epic Games.
**Buyer:** field teams · small studios

#### [NavVis](https://www.navvis.com/)
Laser scanning (VLX/MLX) and indoor digital-twin platform.
**Market:** Strong in industrial, construction and facility contexts; notable European and US enterprise adoption. **Established.**
**Buyer:** facility managers · scan-to-BIM teams

#### [OpenDroneMap](https://opendronemap.org/)
Open-source drone photogrammetry and mapping.
**Market:** Global open-source community; used where cost control and data ownership matter. **Growing (open source).**
**Buyer:** drone operators · GIS teams

#### [Cintoo](https://www.cintoo.com/)
Cloud platform for scan data, BIM comparison and collaboration.
**Market:** Growing in scan-to-BIM and construction QA; relevant across Europe and North America. **Growing.**
**Buyer:** scan-to-BIM teams · construction QA

---


## Coordination, CDE & Construction Management

#### [Autodesk Navisworks](https://www.autodesk.com/products/navisworks/overview)
Model aggregation, clash detection and 4D planning.
**Market:** Very strong wherever Revit is dominant, especially US, CH and DE; widely used in FR too. **Established.**
**Buyer:** BIM managers · coordinators

#### [Solibri](https://www.solibri.com/)
BIM model checking, QA and rule-based coordination.
**Market:** Strong in Nordic and DACH BIM markets; used by demanding BIM-management teams in CH, DE and FR. **Established.**
**Buyer:** BIM managers · model checkers

#### [Autodesk Construction Cloud](https://construction.autodesk.com/)
Cloud CDE for design coordination and construction management.
**Market:** Strong in Autodesk-centric firms; broad US adoption and growing European use. **Established.**
**Buyer:** contractors · design coordinators · owners

#### [Procore](https://www.procore.com/)
Construction project management platform.
**Market:** Dominant in the US; expanding in Europe including CH and DE, though local competitors remain important. **Established.**
**Buyer:** contractors · owners · project managers

#### [BIMcollab](https://www.bimcollab.com/en)
BIM issue management and model coordination (BCF-based).
**Market:** Strong in Europe, especially Netherlands, DACH and CH; relevant to formal BIM coordination. **Growing.**
**Buyer:** BIM coordinators

#### [Revizto](https://revizto.com/en/)
Collaborative 3D model review and issue tracking.
**Market:** Growing internationally; practical for cross-discipline review and issue tracking. **Growing.**
**Buyer:** BIM coordinators · cross-discipline reviewers

#### [Bluebeam](https://www.bluebeam.com/)
PDF markup, drawing review and document collaboration.
**Market:** Extremely strong in US construction; also widely used in CH, DE and FR for drawing review. **Established.**
**Buyer:** contractors · architects · engineers

#### [Bentley ProjectWise](https://www.bentley.com/software/projectwise/)
Enterprise CDE for engineering documents and models.
**Market:** Strong in infrastructure, rail and large public-sector projects; notable in US, DE and CH. **Established.**
**Buyer:** infrastructure owners · engineering firms

#### [Dalux](https://www.dalux.com/)
CDE and construction management platform.
**Market:** Strong in Northern Europe and expanding in DACH; increasingly relevant in CH and DE. **Growing.** Dalux ApS, Copenhagen — founder-owned.
**Buyer:** contractors · site managers · facility owners

#### [Buildagil](https://www.buildagil.com/en)
Swiss project-management and collaboration platform for construction.
**Market:** Particularly relevant in Switzerland; strong local-fit advantage for Swiss projects and stakeholders. **Growing (CH).**
**Buyer:** contractors · owners · architects (Swiss projects)

#### [Trimble Connect](https://www.trimble.com/en/products/trimble-connect)
Cloud collaboration for 3D models and construction data.
**Market:** Broad adoption across construction and MEP workflows; strong in US and Europe. **Established.**
**Buyer:** contractors · MEP teams · BIM coordinators

#### [OpenSpace](https://www.openspace.ai/)
360° photo documentation and remote site monitoring.
**Market:** Strong in US construction; growing European adoption. **Growing.**
**Buyer:** contractors · site teams · owners

#### [Buildots](https://www.buildots.com/)
AI construction progress tracking from site imagery.
**Market:** Enterprise construction-tech adoption; strongest in large contractors and anglophone/European markets. **Growing.**
**Buyer:** large contractors · project controls

#### [Fieldwire](https://www.fieldwire.com/)
Mobile field-management app for tasks, plans and punch lists.
**Market:** Strong with subcontractors and site teams in US and Europe; practical, mobile-first adoption. **Established (field).** Hilti.
**Buyer:** subcontractors · site teams

---


## Sustainability, Performance & Carbon

#### [One Click LCA](https://oneclicklca.com/)
Life-cycle assessment and embodied-carbon calculation, with BIM/IFC integration.
**Market:** Strong in Europe, especially where embodied-carbon regulation is advancing; growing US adoption. **Established.**
**Buyer:** sustainability consultants · architects

#### [EC3](https://www.buildingtransparency.org/tools/ec3/)
Database and tool for low-carbon material procurement, with third-party-verified EPDs.
**Market:** US-origin and particularly relevant to US procurement and carbon benchmarking; useful internationally. **Growing.**
**Buyer:** owners · procurement teams · sustainability consultants

#### [Tally](https://choosetally.com/)
Revit-based whole-building LCA tool.
**Market:** Used where Revit-based sustainability workflows are established; stronger in US and English-speaking markets. **Growing.**
**Buyer:** architects · sustainability consultants

#### [IES VE](https://www.iesve.com/)
Building energy, comfort and performance simulation.
**Market:** Strong in UK/Europe and used by specialized sustainability engineers in CH, DE, FR and US. **Established.**
**Buyer:** sustainability engineers · MEP engineers

#### [Ladybug Tools](https://www.ladybug.tools/index.html#header-slide-show)
Open-source environmental analysis and simulation for Rhino/Grasshopper.
**Market:** Global computational-design community; strong among parametric/sustainability teams. **Growing (open source).**
**Buyer:** computational designers · sustainability engineers

#### [cove.tool](https://www.covetool.com/)
Cloud performance, energy, daylight and carbon analysis for early design.
**Market:** US-origin, growing internationally; appealing to firms wanting accessible performance feedback. **Growing.**
**Buyer:** architects · sustainability leads

#### [EcoTool](https://www.ecotool.org/)
Sustainability and environmental assessment tool — early-phase LCA, embodied carbon and operating energy.
**Market:** Niche/early-stage. Run by EcoTool AG, Basel; KBOB data basis. ⚠ German-language site only. **Emerging (CH).**
**Buyer:** architects · planners

#### [CarbonSpace](https://carbonspace.earth/)
Carbon and environmental intelligence platform — free web-based embodied-carbon estimation from early design.
**Market:** Early-stage/niche. Initiated by MVRDV NEXT; open API to Rhino, Revit and Power BI. ⚠ `carbonspace.tech` is an unrelated company. **Emerging.**
**Buyer:** architects · sustainability leads

---


## Urban Research & Experimental Platforms

#### 
*Less conventional commercial products, and more research, civic-tech or experimental design tools.*

#### [Cityweft](https://www.cityweft.com/)
Urban data and city-design analytics platform; editable 3D site and city models.
**Market:** Niche; relevant to urban analytics and planning innovation. **Experimental.**
**Buyer:** urban planners · architects

#### [Cartes.archi](https://cartes.archi/)
French platform mapping cadastre, PLU zoning, risks, DPE and 3D terrain.
**Market:** France-focused; most relevant to the French architectural ecosystem. **Niche (FR).**
**Buyer:** architects · planners & developers (France)

#### [RoofScape](https://www.mvrdv.com/projects/929/roofscape)
MVRDV research project on activating urban roofs.
**Market:** MVRDV-associated experimental project/platform; niche and concept-led. ⚠ No public app URL — Rotterdams municipal prototype, documented on a case-study page. **Experimental.**
**Buyer:** municipalities · urban planners

#### [SolarScape](https://mvrdv.com/projects/1182/solarscape)
MVRDV research tool for urban solar and daylight potential ("sunspots").
**Market:** Experimental MVRDV-related tool; niche. ⚠ Case-study page only, no standalone app. **Experimental.**
**Buyer:** urban planners · municipalities

#### [MVRDV.Cloud](https://www.mvrdv.com/projects/1186/mvrdvcloud)
MVRDV's experimental cloud archive and research platform.
**Market:** Internal/experimental MVRDV initiative rather than a broad market product. ⚠ No verified public app URL. **Experimental.**
**Buyer:** researchers · archivists

#### [Grasbrook Maker](https://mvrdv.com/stack-magazine/2575/mvrdv-grasbrook-maker-future-of-participatory-urban-design)
Participatory urban-design tool/project by MVRDV.
**Market:** Project-specific participatory-design initiative; niche. ⚠ Prototype only — never released as a product. **Experimental.**
**Buyer:** municipalities · participatory planners

#### [MVRDV NEXT](https://www.mvrdv.com/themes/15/next)
MVRDV's research and innovation unit.
**Market:** Not a product but an R&D group; relevant as an innovation reference. **n/a.**
**Buyer:** n/a — R&D reference

---


## Materials, Products & Specifications

#### [Material Bank](https://www.materialbank.com/)
Fast sampling and material library for architecture and interiors.
**Market:** Strong in US architecture and interiors; expanding internationally including European design markets. 45k+ materials / 450+ brands. **Established.**
**Buyer:** architects · interior designers

#### [Architonic](https://www.architonic.com/)
Product directory and inspiration platform for design professionals.
**Market:** Strong in Europe, especially CH, DE and FR; widely used by architects and interior designers. ⚠ Catalogue figures are self-reported. **Established.**
**Buyer:** architects · interior designers · specifiers

#### [BIMobject](https://www.bimobject.com/en)
Marketplace for manufacturer BIM objects and product data.
**Market:** Global manufacturer-content platform; strong in Europe and growing in North America. **Established.**
**Buyer:** architects · BIM managers · manufacturers

#### [Scawo3D](https://www.scawo3d.com/)
3D product/catalog content and 3D concrete printing (Selective Paste Intrusion).
**Market:** Niche; likely manufacturer- or catalogue-oriented. Research ties to TRR 277 / AMC. **Experimental.**
**Buyer:** manufacturers · fabricators

#### [Arquiz](https://www.arquiz.fr/)
French platform for architecture training, media and project resources.
**Market:** France-oriented; most relevant to the French market. Qualiopi-certified, OPCO-fundable. **Emerging (FR).**
**Buyer:** AEC professionals (France)

#### [AAL Innovation](https://www.aalinnovationai.com/)
AEC innovation and technology platform — Hong Kong AI consultancy and academy (ArchMaster.ai).
**Market:** Niche/early-stage. **Emerging.**
**Buyer:** AEC professionals · firms (Hong Kong)

---

## Market Patterns

The country reads above collapse into four recognizable stacks:

- **US** — Revit + Autodesk Construction Cloud + Procore + Bluebeam, with strong adoption of Enscape, Matterport, OpenSpace, cove.tool and EC3.
- **Switzerland** — a mix of Revit and Archicad, strong Allplan and Dlubal presence, plus locally relevant platforms such as Buildagil; BIMcollab, Solibri and Speckle fit mature BIM environments.
- **Germany** — Allplan, Dlubal RFEM, MagiCAD, Solibri, Dalux and Bentley tools are particularly strong; Revit remains central in many large practices and contractors.
- **France** — Revit and Archicad are both significant; Allplan has a European footprint; OOTI, Cartes.archi and Arquiz are notably France-relevant; Architonic and BIMobject are strong for product content.

**Tags used on every entry:** maturity (*established / growing / emerging / experimental*)
and primary buyer (*architect / engineer / contractor / owner / BIM manager / visualization artist
/ researcher*).

---

*Compiled October 2026. Grouping and descriptions cross-checked against vendor sites and
independent sources; market reads are directional.*
