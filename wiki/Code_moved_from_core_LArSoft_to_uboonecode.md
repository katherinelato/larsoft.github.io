Code moved from core LArSoft to uboonecode
==========================================================================================

Note that all files moved from core LArSoft have copies in their original locations, but with “.sample” appended to the end of the filename.

uBooNE-specific Files from from core LArSoft:

Geometry/gdml/microboone\_5mm.gdml\
Geometry/gdml/microboone.gdml\
Geometry/gdml/microboone/generate\_gdml.pl\
Geometry/gdml/microboone/GenerateMicroBooNEGDML.sh\
Geometry/gdml/microboone\_geo.C\
Geometry/gdml/microboone-granite.gdml\
Geometry/gdml/microboone-granite\_geo.C\
Geometry/gdml/microboone/make\_gdml.pl\
Geometry/gdml/microboone/materials.gdml\
Geometry/gdml/microboone/microboone.gdml\
Geometry/gdml/microboone/microboone-gdml-fragments.xml\
Geometry/gdml/microboone/microboone-gdml-parameters.xml\
Geometry/gdml/microboone/micro-bulk.gdml\
Geometry/gdml/microboone/micro-cathode.gdml\
Geometry/gdml/microboone/micro-cryostatbase.gdml\
Geometry/gdml/microboone/micro-cryostat.gdml\
Geometry/gdml/microboone/micro-defs.gdml\
Geometry/gdml/microboone/micro-electronics.gdml\
Geometry/gdml/microboone/micro-enclosureExtras.gdml\
Geometry/gdml/microboone/micro-enclosure.gdml\
Geometry/gdml/microboone/micro-extramaterials.gdml\
Geometry/gdml/microboone/micro-fieldcage.gdml\
Geometry/gdml/microboone/micro-groundplate.gdml\
Geometry/gdml/microboone/micro-hivplane.gdml\
Geometry/gdml/microboone/micro-motherboards.gdml\
Geometry/gdml/microboone/micro-plane.gdml\
Geometry/gdml/microboone/micro-pmtdef.gdml\
Geometry/gdml/microboone/micro-rotations.gdml\
Geometry/gdml/microboone/micro-tpc.gdml\
Geometry/gdml/microboone/micro-vertplane.gdml\
Geometry/gdml/microboone/micro-wheelsupport.gdml\
Geometry/gdml/microboone/micro-wireplane.gdml\
Geometry/gdml/microboone/micro-world.gdml\
Geometry/gdml/microboone\_nowires.gdml\
Geometry/gdml/microboone/ScriptFragments/cathodegen.pl\
Geometry/gdml/microboone/ScriptFragments/cryo-back\
Geometry/gdml/microboone/ScriptFragments/electrocardplacer.pl\
Geometry/gdml/microboone/ScriptFragments/electropiece.pl\
Geometry/gdml/microboone/ScriptFragments/fieldcagebeamgen.pl\
Geometry/gdml/microboone/ScriptFragments/fieldcagegen.pl\
Geometry/gdml/microboone/ScriptFragments/gen\_cathode.pl\
Geometry/gdml/microboone/ScriptFragments/gen\_cryostat.C\
Geometry/gdml/microboone/ScriptFragments/gen\_fieldcage.pl\
Geometry/gdml/microboone/ScriptFragments/gen\_microplane.C\
Geometry/gdml/microboone/ScriptFragments/gen\_microvertplane.C\
Geometry/gdml/microboone/ScriptFragments/gen\_motherboards.pl\
Geometry/gdml/microboone/ScriptFragments/gen\_pmtrack.pl\
Geometry/gdml/microboone/ScriptFragments/gen\_rails.pl\
Geometry/gdml/microboone/ScriptFragments/gen\_wheelsupportrs.pl\
Geometry/gdml/microboone\_simplegeo.C\
RawData/utils/LArRawInputDriverUBooNE.cxx\
RawData/utils/LArRawInputDriverUBooNE.h\
RawData/utils/LArRawInputSourceUBooNE\_source.cc\
Utilities/databaseutil\_microboone.fcl\
Utilities/detectorproperties\_microboone.fcl\
Utilities/larfft\_microboone.fcl\
Utilities/optical\_reco\_uboone.fcl\
Utilities/sam\_microboone.fcl\
Utilities/services\_microboone.fcl\
Utilities/signalservices\_microboone.fcl\
Utilities/SignalShapingServiceMicroBooNE.h\
Utilities/SignalShapingServiceMicroBooNE\_service.cc\
Utilities/standard\_reco\_uboone.fcl\
Utilities/test/SignalShapingMicroBooNETest\_module.cc\
Utilities/test/sss\_uboone.fcl\
RawData/uboone\_datatypes/beamData.cpp\
RawData/uboone\_datatypes/beamData.h\
RawData/uboone\_datatypes/beamHeader.cpp\
RawData/uboone\_datatypes/beamHeader.h\
RawData/uboone\_datatypes/cardData.cpp\
RawData/uboone\_datatypes/cardData.h\
RawData/uboone\_datatypes/cardDataPMT.cpp\
RawData/uboone\_datatypes/cardDataPMT.h\
RawData/uboone\_datatypes/cardHeader.cpp\
RawData/uboone\_datatypes/cardHeader.h\
RawData/uboone\_datatypes/cardHeaderPMT.cpp\
RawData/uboone\_datatypes/cardHeaderPMT.h\
RawData/uboone\_datatypes/channelData.cpp\
RawData/uboone\_datatypes/channelData.h\
RawData/uboone\_datatypes/channelDataPMT.h\
RawData/uboone\_datatypes/CMakeLists.txt\
RawData/uboone\_datatypes/constants.h\
RawData/uboone\_datatypes/crateData.cpp\
RawData/uboone\_datatypes/crateData.h\
RawData/uboone\_datatypes/crateDataPMT.cpp\
RawData/uboone\_datatypes/crateDataPMT.h\
RawData/uboone\_datatypes/crateHeader.cpp\
RawData/uboone\_datatypes/crateHeader.h\
RawData/uboone\_datatypes/dataHeaderTrailerPMT.h\
RawData/uboone\_datatypes/eventHeaderTrailer.h\
RawData/uboone\_datatypes/eventRecord.cpp\
RawData/uboone\_datatypes/eventRecord.h\
RawData/uboone\_datatypes/evttypes.cpp\
RawData/uboone\_datatypes/evttypes.h\
RawData/uboone\_datatypes/globalHeader.cpp\
RawData/uboone\_datatypes/globalHeader.h\
RawData/uboone\_datatypes/GNUmakefile\
RawData/uboone\_datatypes/gps.cpp\
RawData/uboone\_datatypes/gps.h\
RawData/uboone\_datatypes/gps/trigBoardClock.h\
RawData/uboone\_datatypes/share/boonetypes.h\
RawData/uboone\_datatypes/share/event\_types.h\
RawData/uboone\_datatypes/triggerData.cpp\
RawData/uboone\_datatypes/triggerData.h\
RawData/uboone\_datatypes/windowDataPMT.h\
RawData/uboone\_datatypes/windowHeaderPMT.cpp\
RawData/uboone\_datatypes/windowHeaderPMT.h\
RawData/uboone\_datatypes/write\_read.cc\
CalData/caldata\_microboone.fcl\
CalData/CalWireMicroBooNE\_module.cc\
CalData/test/ffttest\_uboone.fcl\
CalData/test/simwire\_uboone.fcl\
DetSim/detsimmodules\_microboone.fcl\
DetSim/SimWireMicroBooNE\_module.cc\
EventGenerator/GENIE/genie\_microboone.fcl\
EventGenerator/lightsource\_microboone.fcl\
EventGenerator/prodsingleNEST\_uboone.fcl\
EventGenerator/prodsingle\_uboone\_comp.fcl\
EventGenerator/prodsingle\_uboone.fcl\
EventGenerator/singles\_microboone.fcl\
LArG4/largeantmodules\_microboone.fcl\
PhotonPropagation/photpropmodules\_microboone.fcl\
PhotonPropagation/photpropservices\_microboone.fcl\
Simulation/simulationservices\_microboone.fcl\
TriggerAlgo/TrigAnaMicroBoone\_module.cc\
TriggerAlgo/TriggerAlgoMicroBoone.h\
TriggerAlgo/TriggerAlgoMicroBoone\_service.cc