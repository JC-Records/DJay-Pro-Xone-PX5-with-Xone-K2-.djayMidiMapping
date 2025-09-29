# DJay-Pro-Xone-PX5-with-Xone-K2-.djayMidiMapping
# Midi Maps For DJay Pro
{
    USBID = <*I586154008>;
    controls = (

        
        {
            keyPath = "mixer.crossfade";
            midiChannel = <*I15>;
            midiData = <*I4>;
            midiMessageType = <*I3>;
        },
        {
            keyPath = "mixer.externalLineVolume3";
            midiChannel = <*I15>;
            midiData = <*I0>;
            midiMessageType = <*I3>;
        },
        {
            keyPath = "mixer.externalLineVolume1";
            midiChannel = <*I15>;
            midiData = <*I1>;
            midiMessageType = <*I3>;
        },
        {
            keyPath = "mixer.externalLineVolume2";
            midiChannel = <*I15>;
            midiData = <*I2>;
            midiMessageType = <*I3>;
        },
        {
            keyPath = "mixer.externalLineVolume4";
            midiChannel = <*I15>;
            midiData = <*I3>;
            midiMessageType = <*I3>;
            output = { midiData = <*I59>; };
        },
        {
            keyPath = "turntable1.playPause";
            midiChannel = <*I14>;
            midiData = <*I37>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I37>;
                states = (
                    { condition = "playing"; value = <*I5>; },              
                    { condition = "trackLoaded"; values = (<*I1>, <*I0>); },
                    { condition = "noTrack"; values = (<*I3>, <*I0>); }     
                );
            };
        },
        {
            keyPath = "turntable2.playPause";
            midiChannel = <*I14>;
            midiData = <*I38>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I38>;
                states = (
                    { condition = "playing"; value = <*I5>; },
                    { condition = "trackLoaded"; values = (<*I1>, <*I0>); },
                    { condition = "noTrack"; values = (<*I3>, <*I0>); }
                );
            };
        },
        {
            keyPath = "turntable3.playPause";
            midiChannel = <*I14>;
            midiData = <*I36>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I36>;
                states = (
                    { condition = "playing"; value = <*I5>; },
                    { condition = "trackLoaded"; values = (<*I1>, <*I0>); },
                    { condition = "noTrack"; values = (<*I3>, <*I0>); }
                );
            };
        },
        {
            keyPath = "turntable4.playPause";
            midiChannel = <*I14>;
            midiData = <*I39>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I39>;
                states = (
                    { condition = "playing"; value = <*I5>; },
                    { condition = "trackLoaded"; values = (<*I1>, <*I0>); },
                    { condition = "noTrack"; values = (<*I3>, <*I0>); }
                );
            };
        },
        {
            keyPath = "turntable1.cuePositionOrJumpConsideringPlayState1";
            midiChannel = <*I14>;
            midiData = <*I33>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I33>;
                states = (
                    { condition = "loadedNotCued"; values = (<*I1>, <*I0>); }, 
                    { condition = "cued"; value = <*I3>; },                   
                    { condition = "cuePlay"; values = (<*I5>, <*I0>); }       
                );
            };
        },
        {
            keyPath = "turntable2.cuePositionOrJumpConsideringPlayState1";
            midiChannel = <*I14>;
            midiData = <*I34>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I34>;
                states = (
                    { condition = "loadedNotCued"; values = (<*I1>, <*I0>); },
                    { condition = "cued"; value = <*I3>; },
                    { condition = "cuePlay"; values = (<*I5>, <*I0>); }
                );
            };
        },
        {
            keyPath = "turntable3.cuePositionOrJumpConsideringPlayState1";
            midiChannel = <*I14>;
            midiData = <*I32>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I32>;
                states = (
                    { condition = "loadedNotCued"; values = (<*I1>, <*I0>); },
                    { condition = "cued"; value = <*I3>; },
                    { condition = "cuePlay"; values = (<*I5>, <*I0>); }
                );
            };
        },
        {
            keyPath = "turntable4.cuePositionOrJumpConsideringPlayState1";
            midiChannel = <*I14>;
            midiData = <*I35>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I35>;
                states = (
                    { condition = "loadedNotCued"; values = (<*I1>, <*I0>); },
                    { condition = "cued"; value = <*I3>; },
                    { condition = "cuePlay"; values = (<*I5>, <*I0>); }
                );
            };
        },
        {
            keyPath = "turntable1.bpmSync";
            midiChannel = <*I14>;
            midiData = <*I29>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I29>;
                states = (
                    { condition = "synced"; value = <*I1>; },             
                    { condition = "notSynced"; values = (<*I3>, <*I0>); }  
                );
            };
        },
        {
            keyPath = "turntable2.bpmSync";
            midiChannel = <*I14>;
            midiData = <*I30>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I30>;
                states = (
                    { condition = "synced"; value = <*I1>; },
                    { condition = "notSynced"; values = (<*I3>, <*I0>); }
                );
            };
        },
        {
            keyPath = "turntable3.bpmSync";
            midiChannel = <*I14>;
            midiData = <*I28>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I28>;
                states = (
                    { condition = "synced"; value = <*I1>; },
                    { condition = "notSynced"; values = (<*I3>, <*I0>); }
                );
            };
        },
        {
            keyPath = "turntable4.bpmSync";
            midiChannel = <*I14>;
            midiData = <*I31>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I31>;
                states = (
                    { condition = "synced"; value = <*I1>; },
                    { condition = "notSynced"; values = (<*I3>, <*I0>); }
                );
            };
        },
        {
            keyPath = "musicLibrary.load1";
            midiChannel = <*I14>;
            midiData = <*I25>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I25>;
                states = (
                    { condition = "noTrack"; values = (<*I1>, <*I0>); },  
                    { condition = "trackLoaded"; value = <*I3>; }        
                );
            };
        },
        {
            keyPath = "musicLibrary.load2";
            midiChannel = <*I14>;
            midiData = <*I26>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I26>;
                states = (
                    { condition = "noTrack"; values = (<*I1>, <*I0>); },
                    { condition = "trackLoaded"; value = <*I3>; }
                );
            };
        },
        {
            keyPath = "musicLibrary.load3";
            midiChannel = <*I14>;
            midiData = <*I24>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I24>;
                states = (
                    { condition = "noTrack"; values = (<*I1>, <*I0>); },
                    { condition = "trackLoaded"; value = <*I3>; }
                );
            };
        },
        {
            keyPath = "musicLibrary.load4";
            midiChannel = <*I14>;
            midiData = <*I27>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I27>;
                states = (
                    { condition = "noTrack"; values = (<*I1>, <*I0>); },
                    { condition = "trackLoaded"; value = <*I3>; }
                );
            };
        },
        {
            keyPath = "turntable1.autoLoopOnOff";
            midiChannel = <*I14>;
            midiData = <*I53>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I53>;
                states = (
                    { condition = "loop4"; value = <*I5>; },             
                    { condition = "loop8"; value = <*I3>; },              
                    { condition = "loop16"; value = <*I1>; },             
                    { condition = "noLoop"; values = (<*I7>, <*I0>); }   
                );
            };
        },
        {
            keyPath = "turntable2.autoLoopOnOff";
            midiChannel = <*I14>;
            midiData = <*I54>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I54>;
                states = (
                    { condition = "loop4"; value = <*I5>; },
                    { condition = "loop8"; value = <*I3>; },
                    { condition = "loop16"; value = <*I1>; },
                    { condition = "noLoop"; values = (<*I7>, <*I0>); }
                );
            };
        },
        {
            keyPath = "turntable3.autoLoopOnOff";
            midiChannel = <*I14>;
            midiData = <*I52>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I52>;
                states = (
                    { condition = "loop4"; value = <*I5>; },
                    { condition = "loop8"; value = <*I3>; },
                    { condition = "loop16"; value = <*I1>; },
                    { condition = "noLoop"; values = (<*I7>, <*I0>); }
                );
            };
        },
        {
            keyPath = "turntable4.autoLoopOnOff";
            midiChannel = <*I14>;
            midiData = <*I55>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I55>;
                states = (
                    { condition = "loop4"; value = <*I5>; },
                    { condition = "loop8"; value = <*I3>; },
                    { condition = "loop16"; value = <*I1>; },
                    { condition = "noLoop"; values = (<*I7>, <*I0>); }
                );
            };
        },
        {
            keyPath = "turntable1.fx1Enabled";
            midiChannel = <*I14>;
            midiData = <*I41>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I41>;
                states = (
                    { condition = "fxOnDry"; value = <*I7>; },              
                    { condition = "fxWetLow"; values = (<*I5>, <*I0>); },   
                    { condition = "fxWetMid"; values = (<*I3>, <*I0>); },  
                    { condition = "fxWetHigh"; values = (<*I1>, <*I0>); }  
                );
            };
        },
        {
            keyPath = "turntable1.fx2Enabled";
            midiChannel = <*I14>;
            midiData = <*I45>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I45>;
                states = (
                    { condition = "fxOnDry"; value = <*I7>; },
                    { condition = "fxWetLow"; values = (<*I5>, <*I0>); },
                    { condition = "fxWetMid"; values = (<*I3>, <*I0>); },
                    { condition = "fxWetHigh"; values = (<*I1>, <*I0>); }
                );
            };
        },
        {
            keyPath = "turntable1.fx3Enabled";
            midiChannel = <*I14>;
            midiData = <*I49>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I49>;
                states = (
                    { condition = "fxOnDry"; value = <*I7>; },
                    { condition = "fxWetLow"; values = (<*I5>, <*I0>); },
                    { condition = "fxWetMid"; values = (<*I3>, <*I0>); },
                    { condition = "fxWetHigh"; values = (<*I1>, <*I0>); }
                );
            };
        },

        {
            keyPath = "turntable2.fx1Enabled";
            midiChannel = <*I14>;
            midiData = <*I42>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I42>;
                states = (
                    { condition = "fxOnDry"; value = <*I7>; },
                    { condition = "fxWetLow"; values = (<*I5>, <*I0>); },
                    { condition = "fxWetMid"; values = (<*I3>, <*I0>); },
                    { condition = "fxWetHigh"; values = (<*I1>, <*I0>); }
                );
            };
        },
        {
            keyPath = "turntable2.fx2Enabled";
            midiChannel = <*I14>;
            midiData = <*I46>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I46>;
                states = (
                    { condition = "fxOnDry"; value = <*I7>; },
                    { condition = "fxWetLow"; values = (<*I5>, <*I0>); },
                    { condition = "fxWetMid"; values = (<*I3>, <*I0>); },
                    { condition = "fxWetHigh"; values = (<*I1>, <*I0>); }
                );
            };
        },
        {
            keyPath = "turntable2.fx3Enabled";
            midiChannel = <*I14>;
            midiData = <*I50>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I50>;
                states = (
                    { condition = "fxOnDry"; value = <*I7>; },
                    { condition = "fxWetLow"; values = (<*I5>, <*I0>); },
                    { condition = "fxWetMid"; values = (<*I3>, <*I0>); },
                    { condition = "fxWetHigh"; values = (<*I1>, <*I0>); }
                );
            };
        },

        {
            keyPath = "turntable3.fx1Enabled";
            midiChannel = <*I14>;
            midiData = <*I40>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I40>;
                states = (
                    { condition = "fxOnDry"; value = <*I7>; },
                    { condition = "fxWetLow"; values = (<*I5>, <*I0>); },
                    { condition = "fxWetMid"; values = (<*I3>, <*I0>); },
                    { condition = "fxWetHigh"; values = (<*I1>, <*I0>); }
                );
            };
        },
        {
            keyPath = "turntable3.fx2Enabled";
            midiChannel = <*I14>;
            midiData = <*I44>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I44>;
                states = (
                    { condition = "fxOnDry"; value = <*I7>; },
                    { condition = "fxWetLow"; values = (<*I5>, <*I0>); },
                    { condition = "fxWetMid"; values = (<*I3>, <*I0>); },
                    { condition = "fxWetHigh"; values = (<*I1>, <*I0>); }
                );
            };
        },
        {
            keyPath = "turntable3.fx3Enabled";
            midiChannel = <*I14>;
            midiData = <*I48>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I48>;
                states = (
                    { condition = "fxOnDry"; value = <*I7>; },
                    { condition = "fxWetLow"; values = (<*I5>, <*I0>); },
                    { condition = "fxWetMid"; values = (<*I3>, <*I0>); },
                    { condition = "fxWetHigh"; values = (<*I1>, <*I0>); }
                );
            };
        },

        {
            keyPath = "turntable4.fx1Enabled";
            midiChannel = <*I14>;
            midiData = <*I43>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I43>;
                states = (
                    { condition = "fxOnDry"; value = <*I7>; },
                    { condition = "fxWetLow"; values = (<*I5>, <*I0>); },
                    { condition = "fxWetMid"; values = (<*I3>, <*I0>); },
                    { condition = "fxWetHigh"; values = (<*I1>, <*I0>); }
                );
            };
        },
        {
            keyPath = "turntable4.fx2Enabled";
            midiChannel = <*I14>;
            midiData = <*I47>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I47>;
                states = (
                    { condition = "fxOnDry"; value = <*I7>; },
                    { condition = "fxWetLow"; values = (<*I5>, <*I0>); },
                    { condition = "fxWetMid"; values = (<*I3>, <*I0>); },
                    { condition = "fxWetHigh"; values = (<*I1>, <*I0>); }
                );
            };
        },
        {
            keyPath = "turntable4.fx3Enabled";
            midiChannel = <*I14>;
            midiData = <*I51>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I51>;
                states = (
                    { condition = "fxOnDry"; value = <*I7>; },
                    { condition = "fxWetLow"; values = (<*I5>, <*I0>); },
                    { condition = "fxWetMid"; values = (<*I3>, <*I0>); },
                    { condition = "fxWetHigh"; values = (<*I1>, <*I0>); }
                );
            };
        }
        {
            keyPath = "musicLibrary.toggleLibrarySource";
            midiChannel = <*I14>;
            midiData = <*I13>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I13>;
                states = (
                    { condition = "playlistView"; value = <*I3>; },  
                    { condition = "songView"; value = <*I1>; }        
                );
            };
        },
        {
            keyPath = "musicLibrary.libraryBack";
            midiChannel = <*I14>;
            midiData = <*I12>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I12>;
                states = (
                    { condition = "atRoot"; values = (<*I1>, <*I0>); }, 
                    { condition = "canGoBack"; value = <*I5>; }        
                );
            };
        },
        {
            keyPath = "musicLibrary.nextSource";
            midiChannel = <*I14>;
            midiData = <*I14>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I14>;
                states = (
                    { condition = "cycling"; values = (<*I3>, <*I0>); }, 
                    { condition = "idle"; value = <*I0>; }               
                );
            };
        },
        {
            keyPath = "musicLibrary.focusQueue";
            midiChannel = <*I14>;
            midiData = <*I15>;
            midiMessageType = <*I1>;
            output = {
                midiData = <*I15>;
                states = (
                    { condition = "queueActive"; value = <*I7>; },       
                    { condition = "libraryActive"; value = <*I0>; }     
                );
            };
        }
    );  
    customClassName = AllenHeathXonePX5;
    editor = "(null)-5.4.3";
    endpointName = "XONE:PX5";
    schemeVersion = <*I1>;
    supportWebsite = "https://www.allen-heath.com/support/";
    uuid = "90E13B62-5065-4777-A44E-9BAC0A33883F";
    version = <*I2>;
}
