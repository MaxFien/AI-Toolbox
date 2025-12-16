<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Logistiek AI Toolbox</title>
    <script crossorigin src="https://unpkg.com/react@18/umd/react.production.min.js"></script>
    <script crossorigin src="https://unpkg.com/react-dom@18/umd/react-dom.production.min.js"></script>
    <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body>
    <div id="root"></div>
    <script type="text/babel">
        const { useState } = React;

        function LogisticsAIToolbox() {
            const [currentView, setCurrentView] = useState('home');
            const [selectedProcess, setSelectedProcess] = useState(null);
            const [selectedCategory, setSelectedCategory] = useState(null);

            const processes = [
                { id: 'forecasting', name: 'Forecasting', description: 'Voorspellen van transportvraag en capaciteitsbehoefte', icon: '📊', standaloneCount: 7, platformCount: 6 },
                { id: 'order-entry', name: 'Order Entry', description: 'Registreren en verwerken van transportopdrachten', icon: '📝', standaloneCount: 12, platformCount: 2 },
                { id: 'transport-selectie', name: 'Transport Selectie', description: 'Kiezen van vervoerswijze en vervoerder', icon: '🚚', standaloneCount: 5, platformCount: 5 },
                { id: 'enkelvoudige-planning', name: 'Enkelvoudige Transportplanning', description: 'Optimaliseren van individuele routes', icon: '🗺️', standaloneCount: 11, platformCount: 2 },
                { id: 'complexe-planning', name: 'Complexe Transportplanning', description: 'Bundelen van vrachten en samenwerking', icon: '🧩', standaloneCount: 3, platformCount: 7 },
                { id: 'documentatie', name: 'Documentatie', description: 'Genereren en beheren van transportdocumenten', icon: '📄', standaloneCount: 7, platformCount: 2 },
                { id: 'goederen-voorbereiding', name: 'Goederen Voorbereiding', description: 'Laden, picken en klaarzetten van goederen', icon: '📦', standaloneCount: 4, platformCount: 4 },
                { id: 'transport-uitvoering', name: 'Transport Uitvoering', description: 'Real-time monitoren en bijsturen', icon: '🛣️', standaloneCount: 3, platformCount: 5 },
                { id: 'goederen-afleveren', name: 'Goederen Afleveren', description: 'Fysieke aflevering met digitale ondersteuning', icon: '🏠', standaloneCount: 3, platformCount: 6 },
                { id: 'facturatie', name: 'Facturatie en Afwikkeling', description: 'Automatisch genereren van facturen', icon: '💰', standaloneCount: 5, platformCount: 5 },
                { id: 'dashboarding', name: 'Dashboarding', description: 'Visualiseren van KPI\'s en prestaties', icon: '📈', standaloneCount: 4, platformCount: 5 },
                { id: 'communicatie', name: 'Samenwerking en Communicatie', description: 'Informatie delen met stakeholders', icon: '💬', standaloneCount: 10, platformCount: 0 }
            ];

            const toolsData = {
                'order-entry': {
                    standalone: [
                        { name: 'Adabt', url: 'https://www.adabt.com', description: 'AI order entry automation', price: 'Op aanvraag' },
                        { name: 'Shipamax', url: 'https://shipamax.com', description: 'AI document processing voor logistics', price: 'Vanaf €500/maand' },
                        { name: 'Veryfi', url: 'https://www.veryfi.com', description: 'OCR API voor shipping documents', price: 'Vanaf €100/maand' },
                        { name: 'Nanonets', url: 'https://nanonets.com', description: 'Custom OCR API', price: 'Vanaf €99/maand' },
                        { name: 'Rossum', url: 'https://rossum.ai', description: 'Intelligent document processing', price: 'Op aanvraag' },
                        { name: 'Docsumo', url: 'https://www.docsumo.com', description: 'Document AI API', price: 'Vanaf €199/maand' },
                        { name: 'PackageX', url: 'https://packagex.io', description: 'Document capture API', price: 'Op aanvraag' },
                        { name: 'Base64.ai', url: 'https://base64.ai', description: 'Document AI', price: 'Op aanvraag' },
                        { name: 'Hyperverge', url: 'https://hyperverge.co', description: 'AI OCR API', price: 'Op aanvraag' },
                        { name: 'Klearstack', url: 'https://klearstack.com', description: 'Document workflow automation', price: 'Op aanvraag' },
                        { name: 'Send AI', url: 'https://send.ai', description: 'E-mail inbox automatisering + document extractie voor transportorders', price: 'Op aanvraag' },
                        { name: 'Hyperscience', url: 'https://www.hyperscience.com', description: 'AI voor automatisch verwerken van handgeschreven en ongestructureerde logistieke orders', price: 'Op aanvraag' }
                    ],
                    platform: [
                        { name: 'Wenda', url: 'https://wenda-it.com', description: 'Document digitization platform', price: 'Op aanvraag' },
                        { name: 'ARDEM', url: 'https://ardem.com', description: 'OCR + BPO services', price: 'Op aanvraag' }
                    ]
                },
                'forecasting': {
                    standalone: [
                        { name: 'thouSense', url: 'https://thousense.ai', description: 'Standalone demand forecasting SaaS', price: 'Op aanvraag' },
                        { name: 'Datup', url: 'https://datup.ai', description: 'AI demand planning met ERP integratie', price: 'Op aanvraag' },
                        { name: 'pacemaker.ai', url: 'https://www.pacemaker.ai', description: 'ML forecasting plugin', price: 'Op aanvraag' },
                        { name: 'Antuit.ai', url: 'https://www.antuit.ai', description: 'Demand forecasting API', price: 'Op aanvraag' },
                        { name: 'C3 AI', url: 'https://c3.ai', description: 'Enterprise AI forecasting', price: 'Op aanvraag' },
                        { name: 'anyLogistix', url: 'https://anylogistix.com', description: 'Simulatie en optimalisatie voor complexe netwerk- en freight-planning', price: 'Op aanvraag' },
                        { name: 'GMDH Streamline', url: 'https://gmdhsoftware.com', description: 'Demand forecasting en voorraadoptimalisatie voor MKB met variabele logistieke vraag', price: 'Vanaf €160/maand' }
                    ],
                    platform: [
                        { name: 'Blue Yonder', url: 'https://blueyonder.com', description: 'Supply chain platform met AI', price: 'Enterprise pricing' },
                        { name: 'o9 Solutions', url: 'https://o9solutions.com', description: 'Integrated planning platform', price: 'Enterprise pricing' },
                        { name: 'Kinaxis', url: 'https://www.kinaxis.com', description: 'Supply chain planning platform', price: 'Enterprise pricing' },
                        { name: 'RELEX Solutions', url: 'https://www.relexsolutions.com', description: 'Supply chain planning met ML', price: 'Op aanvraag' },
                        { name: 'Transmetrics', url: 'https://www.transmetrics.ai', description: 'Logistics optimization platform', price: 'Op aanvraag' },
                        { name: 'SAS for Supply Chain', url: 'https://www.sas.com/nl_nl/', description: 'Geavanceerde AI-modellen voor demand sensing en transportvolume voorspelling', price: 'Op aanvraag' }
                    ]
                },
                'transport-selectie': {
                    standalone: [
                        { name: 'Wisor', url: 'https://wisor.ai', description: 'AI-assistent die automatisch tarieven verzamelt en vergelijkt tussen carriers en modaliteiten', price: 'Op aanvraag' },
                        { name: 'Raft AI', url: 'https://raft.ai', description: 'AI-workflow platform met automatische route-beslissingen voor verladers en forwarders', price: 'Op aanvraag' },
                        { name: 'Kontainers', url: 'https://kontainers.com', description: 'Platform dat AI gebruikt om complexe zeetarieven te berekenen en beste routes/carriers te kiezen', price: 'Op aanvraag' },
                        { name: 'Xeneta', url: 'https://www.xeneta.com', description: 'Real-time benchmark van vrachttarieven (zee en lucht) wereldwijd voor slimme carrier selectie', price: 'Op aanvraag' },
                        { name: 'GoRoutr', url: 'https://goroutr.com', description: 'AI tool die beste koeriersdiensten en tarieven voor e-commerce zendingen vergelijkt', price: 'Op aanvraag' }
                    ],
                    platform: [
                        { name: 'CargoWise', url: 'https://www.cargowise.com', description: 'Digital freight forwarder platform met AI carrier selectie en compliance', price: 'Op aanvraag' },
                        { name: 'Flexport', url: 'https://www.flexport.com', description: 'AI-ondersteunde multimodale transportplanner met data-driven carrier/routekeuze', price: 'Op aanvraag' },
                        { name: 'Magaya', url: 'https://www.magaya.com', description: 'Freight forwarding suite met AI-gestuurde transportkeuze en tracking', price: 'Op aanvraag' },
                        { name: 'Shippeo', url: 'https://www.shippeo.com', description: 'Real-time zichtbaarheid en ETA voorspelling over multimodale transporten', price: 'Op aanvraag' },
                        { name: 'Transporeon', url: 'https://www.transporeon.com/nl/', description: 'Toonaangevend platform voor vracht- en capaciteitstoewijzing met AI carrier selectie', price: 'Op aanvraag' }
                    ]
                },
                'enkelvoudige-planning': {
                    standalone: [
                        { name: 'Route4Me', url: 'https://route4me.com', description: 'Route optimization SaaS', price: 'Vanaf €199/maand' },
                        { name: 'Circuit for Teams', url: 'https://getcircuit.com/teams', description: 'Route planning app', price: 'Vanaf €100/maand' },
                        { name: 'Upper', url: 'https://www.upperinc.com', description: 'AI route planner', price: 'Vanaf €99/maand' },
                        { name: 'OptimoRoute', url: 'https://optimoroute.com', description: 'Route optimization tool', price: 'Vanaf €39/maand' },
                        { name: 'Routific', url: 'https://routific.com', description: 'Smart routing SaaS', price: 'Vanaf €49/maand' },
                        { name: 'MyRouteOnline', url: 'https://www.myrouteonline.com', description: 'AI route planner', price: 'Vanaf €29/maand' },
                        { name: 'SmartRoutes', url: 'https://smartroutes.io', description: 'Route planning tool', price: 'Vanaf €59/maand' },
                        { name: 'RouteXL', url: 'https://www.routexl.com', description: 'Simple route optimizer', price: 'Gratis - €49/maand' },
                        { name: 'Speedy Route', url: 'https://www.speedyroute.com', description: 'Route planner', price: 'Gratis - €20/maand' },
                        { name: 'Beans AI', url: 'https://beans.ai', description: 'Route optimization API', price: 'Op aanvraag' },
                        { name: 'Gurobi', url: 'https://www.gurobi.com', description: 'Optimalisatie-engine voor custom VRP-oplossingen en TMS verbetering', price: 'Vanaf €2.700/jaar' }
                    ],
                    platform: [
                        { name: 'WorkWave', url: 'https://www.workwave.com', description: 'Field service platform met routing', price: 'Vanaf €50/maand' },
                        { name: 'Onfleet', url: 'https://onfleet.com', description: 'Delivery management platform', price: 'Vanaf €149/maand' }
                    ]
                },
                'complexe-planning': {
                    standalone: [
                        { name: 'Despatch Cloud', url: 'https://despatchcloud.com', description: 'AI-routecomposer voor grote vrachten en capaciteits-combinaties', price: 'Op aanvraag' },
                        { name: 'Movera', url: 'https://www.moversolutions.nl', description: 'Nederlandse tool gespecialiseerd in AI-gedreven route-optimalisatie en ritplanning', price: 'Op aanvraag' },
                        { name: 'Swarm', url: 'https://www.getswarm.io', description: 'AI-platform dat vrachten dynamisch bundelt en routes optimaliseert', price: 'Op aanvraag' }
                    ],
                    platform: [
                        { name: 'FourKites', url: 'https://www.fourkites.com', description: 'Real-time zichtbaarheid met predictive ETA en geavanceerde planning suggesties', price: 'Op aanvraag' },
                        { name: 'Project44', url: 'https://www.project44.com', description: 'Real-time transportvisibiliteit en predictive analytics voor planning bij verstoringen', price: 'Op aanvraag' },
                        { name: 'Fleet TMS', url: 'https://get-fleet.com', description: 'Complete planning met multi-carrier support en AI optimalisaties', price: 'Op aanvraag' },
                        { name: 'Paragon TMS', url: 'https://www.paragonrouting.com', description: 'Geavanceerde algoritmische planningsengine met constraint-based planning', price: 'Op aanvraag' },
                        { name: 'ORTEC', url: 'https://ortec.com/nl/', description: 'Toonaangevende Europese speler met AI-optimalisatie voor complexe VRP en FTL/LTL vrachten', price: 'Op aanvraag' },
                        { name: 'PTV Group', url: 'https://www.ptvgroup.com/en/', description: 'Multi-depot VRP en route-optimalisatie in complexe, dynamische netwerken', price: 'Op aanvraag' },
                        { name: 'Optilogic', url: 'https://www.optilogic.com', description: 'Supply chain planning met digitale tweelingen en AI netwerkoptimalisatie', price: 'Op aanvraag' }
                    ]
                },
                'documentatie': {
                    standalone: [
                        { name: 'Klippa', url: 'https://www.klippa.com', description: 'Nederlandse AI-document-extractie voor logistiek (B/L, CMR, facturen, pakbonnen)', price: 'Op aanvraag' },
                        { name: 'Parseur', url: 'https://parseur.com', description: 'AI parser die vrachtbrieven en afleverbonnen omzet in gestructureerde data', price: 'Vanaf €49/maand' },
                        { name: 'Ondox', url: 'https://www.ondox.ai', description: 'AI voor end-to-end logistieke document-workflow (B/L, POD, facturen)', price: 'Op aanvraag' },
                        { name: 'Send AI', url: 'https://send.ai', description: 'E-mail inbox automatisering met document extractie en CMR archivering', price: 'Op aanvraag' },
                        { name: 'Tesseron', url: 'https://www.tesseron.eu', description: 'Nederlandse oplossing voor digitale verwerking van e-CMR en transportdocumenten met AI validatie', price: 'Op aanvraag' },
                        { name: 'Inbenta', url: 'https://www.inbenta.com', description: 'AI voor automatisch genereren en invullen van formulieren zoals douane-aangiftes', price: 'Op aanvraag' },
                        { name: 'Kofax', url: 'https://www.kofax.com', description: 'Intelligent document processing om data uit logistieke documenten te extraheren', price: 'Op aanvraag' }
                    ],
                    platform: [
                        { name: 'Doxis', url: 'https://www.doxis.com/nl/', description: 'ECM/CSP platform met AI voor classificatie en extractie uit complexe logistieke documenten', price: 'Op aanvraag' },
                        { name: 'OpenText', url: 'https://www.opentext.nl', description: 'ECM-suite met AI voor beheer van logistieke documenten met focus op compliance', price: 'Op aanvraag' }
                    ]
                },
                'goederen-voorbereiding': {
                    standalone: [
                        { name: 'RightHand Robotics', url: 'https://www.righthandrobotics.com', description: 'AI-gebaseerde picking robots voor order voorbereiding', price: 'Op aanvraag' },
                        { name: 'Pickwise', url: 'https://pickwise.ai', description: 'AI-gestuurde WMS augmentor die pick-planning en zone-assignments verbetert', price: 'Op aanvraag' },
                        { name: 'Packsize', url: 'https://www.packsize.com', description: 'Right-Sized Packaging met AI om optimale doosgrootte te berekenen en produceren', price: 'Op aanvraag' },
                        { name: 'Cubiscan', url: 'https://cubiscan.com', description: 'Automatische dimensie- en gewichtsmeting voor optimale beladingsplanning', price: 'Op aanvraag' }
                    ],
                    platform: [
                        { name: 'GreyOrange', url: 'https://www.greyorange.com', description: 'AI-robotsystemen voor warehouse picking & sorting met machine learning', price: 'Op aanvraag' },
                        { name: 'Locus Robotics', url: 'https://locusrobotics.com', description: 'Autonome mobiele robots met AI-gebaseerde warehouse orderslotting', price: 'Op aanvraag' },
                        { name: '6 River Systems', url: 'https://6river.com', description: 'Collaborative warehouse bots met AI-workflowoptimalisatie', price: 'Op aanvraag' },
                        { name: 'Dematic', url: 'https://www.dematic.com/nl-nl/', description: 'WMS en automatisering met AI voor optimalisatie van Put-away en Picking strategieën', price: 'Op aanvraag' }
                    ]
                },
                'transport-uitvoering': {
                    standalone: [
                        { name: 'Peripass', url: 'https://www.peripass.com/nl/', description: 'Nederlandse Yard Management tool die AI gebruikt om vrachtwagenbewegingen te optimaliseren', price: 'Op aanvraag' },
                        { name: 'Parkd', url: 'https://www.parkd.com/nl/', description: 'Nederlandse tool die voertuigdata en AI gebruikt om automatisch parkeerkosten te registreren', price: 'Op aanvraag' },
                        { name: 'Tive', url: 'https://www.tive.com', description: 'Real-time IoT/AI-trackers die locatie en omgevingscondities monitoren', price: 'Op aanvraag' }
                    ],
                    platform: [
                        { name: 'FourKites', url: 'https://www.fourkites.com', description: 'Platform voor live tracking met AI alerts en predictive ETA', price: 'Op aanvraag' },
                        { name: 'Project44', url: 'https://www.project44.com', description: 'Predictive visibiliteit met AI forecasting voor verstoringen', price: 'Op aanvraag' },
                        { name: 'Wialon', url: 'https://wialon.com', description: 'GPS-tracking met telematica en AI-gebaseerde driver scoring', price: 'Op aanvraag' },
                        { name: 'Samsara', url: 'https://www.samsara.com', description: 'AI-gestuurde telematica met dashcams en predictive maintenance', price: 'Op aanvraag' },
                        { name: 'Verizon Connect', url: 'https://www.verizonconnect.com', description: 'AI-fleet en operations platform met real-time monitoring', price: 'Op aanvraag' }
                    ]
                },
                'goederen-afleveren': {
                    standalone: [
                        { name: 'Routific', url: 'https://routific.com', description: 'Last-mile dispatching met AI-delivery ETA', price: 'Vanaf €49/maand' },
                        { name: 'Simple Delivery', url: 'https://simpledelivery.nl', description: 'Nederlandse mobiele app voor PoD, tracking en last-mile planning voor MKB', price: 'Vanaf €49/maand' },
                        { name: 'e-Delivery', url: 'https://www.e-delivery.net', description: 'Complete oplossing voor mobiele Proof of Delivery met foto\'s en GPS', price: 'Vanaf €15/maand' }
                    ],
                    platform: [
                        { name: 'FarEye', url: 'https://www.fareye.com', description: 'AI-gestuurd delivery orchestration met ETA en event-driven notifications', price: 'Op aanvraag' },
                        { name: 'Onfleet', url: 'https://onfleet.com', description: 'Delivery management platform met route execution en real-time updates', price: 'Vanaf €149/maand' },
                        { name: 'Bringg', url: 'https://www.bringg.com', description: 'Customer-centric delivery orchestration met AI ETA en partner-management', price: 'Op aanvraag' },
                        { name: 'DispatchTrack', url: 'https://dispatchtrack.com', description: 'AI-predictive last-mile delivery met customer alerts', price: 'Op aanvraag' },
                        { name: 'Alpega TMS', url: 'https://www.alpegagroup.com', description: 'TMS met modules voor mobiele digitale PoD en in-cab systemen', price: 'Op aanvraag' },
                        { name: 'Routematch', url: 'https://routematch.com', description: 'AI-platform dat ETA\'s voorspelt en klantcommunicatie over afleverstatus regelt', price: 'Op aanvraag' }
                    ]
                },
                'facturatie': {
                    standalone: [
                        { name: 'Invoiced', url: 'https://www.invoiced.com', description: 'Automated invoice lifecycle met AI matching voor logistics invoices', price: 'Vanaf €130/maand' },
                        { name: 'Stampli', url: 'https://www.stampli.com', description: 'AI-gestuurde AP automation en workflow voor logistiek', price: 'Op aanvraag' },
                        { name: 'Trax', url: 'https://www.traxtech.com', description: 'Toonaangevende AI freight audit oplossing voor automatische factuurcontrole', price: 'Op aanvraag' },
                        { name: 'ControlPay', url: 'https://www.controlpay.com', description: 'Nederlandse AI-gebaseerde factuurcontrole en betaling voor logistiek', price: 'Op aanvraag' },
                        { name: 'Shipmate', url: 'https://www.shipmate.nl', description: 'Automatisering van labels, verzenddocumenten en factuurafwikkeling met vervoerders', price: 'Op aanvraag' }
                    ],
                    platform: [
                        { name: 'Emagia', url: 'https://www.emagia.com', description: 'AI-automatisering van AR/cash application specifiek voor logistiek/transport', price: 'Op aanvraag' },
                        { name: 'Tipalti', url: 'https://tipalti.com', description: 'End-to-end payables met auto-match voor logistieke facturen', price: 'Op aanvraag' },
                        { name: 'Procurify', url: 'https://www.procurify.com', description: 'Purchase-to-pay workflows met AI controls', price: 'Op aanvraag' },
                        { name: 'Tungsten Automation', url: 'https://www.tungstenautomation.com', description: 'AI Purchase-to-Pay automatisering voor complexe logistieke facturatie', price: 'Op aanvraag' },
                        { name: 'Logiport', url: 'https://logiport.nl', description: 'Nederlandse TMS met geïntegreerde automatische facturatie op basis van gerealiseerde ritten', price: 'Op aanvraag' }
                    ]
                },
                'dashboarding': {
                    standalone: [
                        { name: 'Wisor Dashboards', url: 'https://wisor.ai', description: 'Logistieke KPI dashboards met AI insights', price: 'Op aanvraag' },
                        { name: 'LiveEO', url: 'https://live-eo.com', description: 'AI-analytics voor visibility, performance en environmental KPIs', price: 'Op aanvraag' },
                        { name: 'Qlik Sense', url: 'https://www.qlik.com/nl', description: 'BI-platform met AI-ondersteunde associatieve zoek voor logistieke KPIs', price: 'Op aanvraag' },
                        { name: 'Peekstoom', url: 'https://peekstoom.com', description: 'Nederlandse BI-consultancy met specifieke logistieke BI-oplossingen voor MKB', price: 'Op aanvraag' }
                    ],
                    platform: [
                        { name: 'FourKites Analytics', url: 'https://www.fourkites.com', description: 'Real-time transport analytics en KPI dashboards', price: 'Op aanvraag' },
                        { name: 'Project44 Analytics', url: 'https://www.project44.com', description: 'Predictive analytics dashboards voor transport management', price: 'Op aanvraag' },
                        { name: 'Blue Yonder Analytics', url: 'https://blueyonder.com', description: 'AI-powered supply chain analytics en dashboarding', price: 'Enterprise pricing' },
                        { name: 'Exspeedite', url: 'https://exspeedite.com', description: 'TMS met ingebouwde AI-analytics voor MKB transport (utilization, winstgevendheid)', price: 'Op aanvraag' },
                        { name: 'Dataiku', url: 'https://www.dataiku.com', description: 'Enterprise AI-platform voor voorspellende logistieke modellen en visualisaties', price: 'Op aanvraag' }
                    ]
                },
                'communicatie': {
                    standalone: [
                        { name: 'Text App', url: 'https://www.text.com', description: 'AI chatbot voor logistics', price: 'Op aanvraag' },
                        { name: 'Aunoa.ai', url: 'https://aunoa.ai', description: 'Transport chatbot tool', price: 'Op aanvraag' },
                        { name: 'Tring AI', url: 'https://tringlabs.ai', description: 'Logistics voice & chatbot', price: 'Op aanvraag' },
                        { name: 'Robofy', url: 'https://www.robofy.ai', description: 'AI chatbot builder', price: 'Vanaf €19/maand' },
                        { name: 'Copilot.live', url: 'https://copilot.live', description: 'Chatbot platform', price: 'Vanaf €29/maand' },
                        { name: 'Streebo', url: 'https://www.streebo.com', description: 'WhatsApp chatbot voor logistics', price: 'Op aanvraag' },
                        { name: 'ProProfs Chat', url: 'https://www.proprofschat.com', description: 'Chatbot tool', price: 'Vanaf €19/maand' },
                        { name: 'Intercom', url: 'https://www.intercom.com', description: 'AI messaging platform', price: 'Vanaf €74/maand' },
                        { name: 'Drift', url: 'https://www.drift.com', description: 'Conversational AI platform', price: 'Op aanvraag' },
                        { name: 'Ada', url: 'https://www.ada.cx', description: 'AI chatbot platform', price: 'Op aanvraag' }
                    ],
                    platform: []
                }
            };

            const getTools = (processId, category) => {
                if (!toolsData[processId]) return [];
                return toolsData[processId][category] || [];
            };

            if (currentView === 'home') {
                return (
                    <div className="min-h-screen bg-gradient-to-br from-blue-50 to-indigo-100 p-6">
                        <div className="max-w-7xl mx-auto">
                            <div className="text-center mb-12">
                                <h1 className="text-4xl font-bold text-gray-800 mb-4">🚛 Logistiek AI Toolbox</h1>
                                <p className="text-gray-600 text-lg max-w-2xl mx-auto">
                                    Ontdek AI-tools voor elk logistiek proces. Kies tussen standalone tools of complete platforms met AI-functionaliteit.
                                </p>
                            </div>

                            <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                                {processes.map((process) => (
                                    <div key={process.id} onClick={() => { setSelectedProcess(process); setCurrentView('process'); }}
                                        className="bg-white rounded-lg shadow-md hover:shadow-xl transition-all cursor-pointer p-6 border-2 border-transparent hover:border-blue-500">
                                        <div className="text-5xl mb-4">{process.icon}</div>
                                        <h3 className="text-xl font-bold text-gray-800 mb-2">{process.name}</h3>
                                        <p className="text-gray-600 text-sm mb-4">{process.description}</p>
                                        <div className="flex gap-4 text-sm">
                                            <div className="flex items-center gap-1 text-green-600">
                                                <span className="text-lg">✨</span>
                                                <span className="font-semibold">{process.standaloneCount}</span>
                                                <span className="text-gray-500">standalone</span>
                                            </div>
                                            <div className="flex items-center gap-1 text-blue-600">
                                                <span className="text-lg">📦</span>
                                                <span className="font-semibold">{process.platformCount}</span>
                                                <span className="text-gray-500">platforms</span>
                                            </div>
                                        </div>
                                    </div>
                                ))}
                            </div>

                            <div className="mt-12 bg-white rounded-lg shadow-md p-8">
                                <h2 className="text-2xl font-bold text-gray-800 mb-4">💡 Over deze toolbox</h2>
                                <div className="space-y-3 text-gray-700">
                                    <p>Deze toolbox helpt MKB-bedrijven in de logistieke sector bij het vinden van geschikte AI-tools.</p>
                                    <div className="flex items-start gap-3">
                                        <span className="text-green-600 text-xl">✨</span>
                                        <div><strong className="text-green-700">Standalone AI-tools:</strong> Specifieke AI-functionaliteit die je plug-and-play kunt toevoegen aan je bestaande systemen.</div>
                                    </div>
                                    <div className="flex items-start gap-3">
                                        <span className="text-blue-600 text-xl">📦</span>
                                        <div><strong className="text-blue-700">Platforms met AI:</strong> Complete TMS/WMS/ERP systemen met ingebouwde AI-modules.</div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                );
            }

            if (currentView === 'process' && selectedProcess) {
                return (
                    <div className="min-h-screen bg-gradient-to-br from-blue-50 to-indigo-100 p-6">
                        <div className="max-w-5xl mx-auto">
                            <button onClick={() => { setCurrentView('home'); setSelectedProcess(null); }}
                                className="flex items-center gap-2 text-gray-600 hover:text-gray-800 mb-6 transition">
                                <span>←</span> Terug naar overzicht
                            </button>

                            <div className="bg-white rounded-lg shadow-xl p-8 mb-8">
                                <div className="flex items-center gap-4 mb-4">
                                    <span className="text-6xl">{selectedProcess.icon}</span>
                                    <div>
                                        <h1 className="text-3xl font-bold text-gray-800">{selectedProcess.name}</h1>
                                        <p className="text-gray-600">{selectedProcess.description}</p>
                                    </div>
                                </div>
                            </div>

                            <div className="grid grid-cols-1 md:grid-cols-2 gap-6">
                                <div onClick={() => { setSelectedCategory('standalone'); setCurrentView('tools'); }}
                                    className="bg-gradient-to-br from-green-50 to-emerald-100 rounded-lg shadow-lg hover:shadow-xl transition-all cursor-pointer p-8 border-2 border-transparent hover:border-green-500">
                                    <div className="flex items-center gap-3 mb-4">
                                        <span className="text-green-600 text-3xl">✨</span>
                                        <h2 className="text-2xl font-bold text-green-800">Standalone AI-tools</h2>
                                    </div>
                                    <p className="text-gray-700 mb-4">Specifieke AI-functionaliteit die je plug-and-play kunt toevoegen aan je bestaande systemen.</p>
                                    <div className="flex items-center justify-between">
                                        <span className="text-3xl font-bold text-green-600">{selectedProcess.standaloneCount}</span>
                                        <span className="text-green-600 text-2xl">→</span>
                                    </div>
                                    <p className="text-sm text-green-700 mt-2">{selectedProcess.standaloneCount === 0 ? 'Geen standalone tools beschikbaar' : 'Bekijk tools →'}</p>
                                </div>

                                <div onClick={() => { setSelectedCategory('platform'); setCurrentView('tools'); }}
                                    className="bg-gradient-to-br from-blue-50 to-indigo-100 rounded-lg shadow-lg hover:shadow-xl transition-all cursor-pointer p-8 border-2 border-transparent hover:border-blue-500">
                                    <div className="flex items-center gap-3 mb-4">
                                        <span className="text-blue-600 text-3xl">📦</span>
                                        <h2 className="text-2xl font-bold text-blue-800">Platforms met AI</h2>
                                    </div>
                                    <p className="text-gray-700 mb-4">Complete TMS/WMS/ERP systemen met ingebouwde AI-modules en uitgebreide functionaliteit.</p>
                                    <div className="flex items-center justify-between">
                                        <span className="text-3xl font-bold text-blue-600">{selectedProcess.platformCount}</span>
                                        <span className="text-blue-600 text-2xl">→</span>
                                    </div>
                                    <p className="text-sm text-blue-700 mt-2">{selectedProcess.platformCount === 0 ? 'Geen platforms beschikbaar' : 'Bekijk platforms →'}</p>
                                </div>
                            </div>

                            <div className="mt-8 bg-yellow-50 border-l-4 border-yellow-500 p-6 rounded-lg">
                                <h3 className="font-semibold text-yellow-800 mb-2">💡 Wat is het verschil?</h3>
                                <div className="space-y-2 text-sm text-gray-700">
                                    <p><strong>Standalone tools</strong> zijn specifieke AI-oplossingen die je naast je huidige systemen kunt gebruiken. Perfect voor MKB dat nog geen groot TMS heeft of specifieke functionaliteit wil toevoegen.</p>
                                    <p><strong>Platforms</strong> zijn complete systemen die je hele transport/warehouse/logistiek proces ondersteunen. Geschikt voor bedrijven die een alles-in-één oplossing zoeken.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                );
            }

            if (currentView === 'tools' && selectedProcess && selectedCategory) {
                const tools = getTools(selectedProcess.id, selectedCategory);
                const categoryName = selectedCategory === 'standalone' ? 'Standalone AI-tools' : 'Platforms met AI';

                return (
                    <div className="min-h-screen bg-gradient-to-br from-blue-50 to-indigo-100 p-6">
                        <div className="max-w-6xl mx-auto">
                            <button onClick={() => { setCurrentView('process'); setSelectedCategory(null); }}
                                className="flex items-center gap-2 text-gray-600 hover:text-gray-800 mb-6 transition">
                                <span>←</span> Terug naar categorie keuze
                            </button>

                            <div className="bg-white rounded-lg shadow-xl p-8 mb-8">
                                <div className="flex items-center gap-4 mb-2">
                                    <span className="text-4xl">{selectedCategory === 'standalone' ? '✨' : '📦'}</span>
                                    <div>
                                        <h1 className="text-3xl font-bold text-gray-800">{categoryName}</h1>
                                        <p className="text-gray-600">Voor {selectedProcess.name}</p>
                                    </div>
                                </div>
                            </div>

                            {tools.length === 0 ? (
                                <div className="bg-white rounded-lg shadow-md p-12 text-center">
                                    <p className="text-gray-600 text-lg mb-4">Er zijn momenteel geen {categoryName.toLowerCase()} beschikbaar voor dit proces.</p>
                                    <p className="text-gray-500 text-sm">Dit proces vereist vaak volledige systeem integratie of fysieke infrastructuur.</p>
                                </div>
                            ) : (
                                <>
                                    <div className={selectedCategory === 'standalone' ? 'mb-6 bg-green-50 border-l-4 border-green-500 p-6 rounded-lg' : 'mb-6 bg-blue-50 border-l-4 border-blue-500 p-6 rounded-lg'}>
                                        <p className="text-gray-700">
                                            {selectedCategory === 'standalone' 
                                                ? `Gevonden: ${tools.length} standalone AI-tools die je kunt integreren met je bestaande systemen.`
                                                : `Gevonden: ${tools.length} complete platforms met AI-functionaliteit voor ${selectedProcess.name.toLowerCase()}.`}
                                        </p>
                                    </div>

                                    <div className="grid grid-cols-1 md:grid-cols-2 gap-6">
                                        {tools.map((tool, index) => (
                                            <div key={index} className="bg-white rounded-lg shadow-md hover:shadow-lg transition-all p-6 border border-gray-200">
                                                <h4 className="text-lg font-bold text-gray-800 mb-2">{tool.name}</h4>
                                                <p className="text-gray-600 text-sm mb-3">{tool.description}</p>
                                                <div className="flex items-center justify-between">
                                                    <span className="text-sm font-semibold text-green-600">{tool.price}</span>
                                                    <a href={tool.url} target="_blank" rel="noopener noreferrer"
                                                        className="text-blue-600 hover:text-blue-700 text-sm font-semibold flex items-center gap-1">
                                                        Bezoek website →
                                                    </a>
                                                </div>
                                            </div>
                                        ))}
                                    </div>
                                </>
                            )}

                            <div className="mt-8 bg-white rounded-lg shadow-md p-6">
                                <h3 className="font-semibold text-gray-800 mb-3">📋 Nog geen tool gevonden?</h3>
                                <p className="text-gray-600 text-sm mb-4">
                                    Deze toolbox wordt regelmatig bijgewerkt. Mis je een tool of heb je suggesties? 
                                    Laat het ons weten via feedback@logistiek-ai-toolbox.nl
                                </p>
                                <button onClick={() => { setCurrentView('home'); setSelectedProcess(null); setSelectedCategory(null); }}
                                    className="flex items-center gap-2 text-blue-600 hover:text-blue-700 font-semibold">
                                    <span>🏠</span> Terug naar alle processen
                                </button>
                            </div>
                        </div>
                    </div>
                );
            }

            return null;
        }

        ReactDOM.createRoot(document.getElementById('root')).render(<LogisticsAIToolbox />);
    </script>
</body>
</html>
