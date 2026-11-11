# Évaluation Sonore 

[Uploadi<?xml version='1.0' encoding='utf-8'?>
<mlt LC_NUMERIC="en_US.UTF-8" producer="main_bin" root="C:/Users/2489560/OneDrive - Collège Montmorency/Multimédia/TP3" version="7.43.0">
 <profile colorspace="709" description="HD 1080p 30 fps" display_aspect_den="9" display_aspect_num="16" frame_rate_den="1" frame_rate_num="30" height="1080" progressive="1" sample_aspect_den="1" sample_aspect_num="1" width="1920"/>
 <producer id="producer0" in="00:00:00.000" out="00:06:05.033">
  <property name="length">2147483647</property>
  <property name="eof">continue</property>
  <property name="resource">black</property>
  <property name="aspect_ratio">1</property>
  <property name="mlt_service">color</property>
  <property name="kdenlive:playlistid">black_track</property>
  <property name="mlt_image_format">rgba</property>
  <property name="set.test_audio">0</property>
 </producer>
 <chain id="chain0" out="00:00:42.733">
  <property name="length">1283</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2489560/Downloads/STORM_Pluie et orage (ID 0124)_LaSonotheque.fr.wav</property>
  <property name="mlt_service">avformat-novalidate</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">16</property>
  <property name="kdenlive:control_uuid">{67424e50-2c37-4dc1-93e4-860bc06303f4}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">7546030</property>
  <property name="kdenlive:file_hash">006887a786320d29c739485dadbfc712</property>
  <property name="kdenlive:record_start_frame">-1</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:meta.extractor.Bitrate:">1411 kb/s</property>
  <property name="kdenlive:meta.extractor.Copyright:">CC0 / WTFPL / Public domain</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s16</property>
  <property name="meta.media.0.codec.sample_rate">44100</property>
  <property name="meta.media.0.codec.channels">2</property>
  <property name="meta.media.0.codec.layout">independent</property>
  <property name="meta.media.0.codec.name">pcm_s16le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 16-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">1411200</property>
  <property name="meta.attr.comment.markup">Rain and storm</property>
  <property name="meta.attr.encoded_by.markup">BigSoundBank.com</property>
  <property name="meta.attr.originator_reference.markup">0124</property>
  <property name="meta.attr.date.markup">2006-09-30</property>
  <property name="meta.attr.time_reference.markup">0</property>
  <property name="meta.attr.coding_history.markup">A=PCM,F=44100,W=16,M=stereo</property>
  <property name="meta.attr.copyright.markup">CC0 / WTFPL / Public domain</property>
  <property name="meta.attr.IKEY.markup">orage,pluie,eau,pleut,foudre,tonnerre,coup,averse,rain,thunderstorm,thunder,ambiance,clash,atmosphere,soundscape,raining,kick,nature,grondement,gronder,tonner,eclair,grosse,gros,fort,forte,thunderstruck</property>
  <property name="meta.attr.IARL.markup">48.576346,1.876454</property>
  <property name="xml">was here</property>
  <property name="mute_on_pause">0</property>
  <property name="set.test_audio">0</property>
  <property name="set.test_image">1</property>
 </chain>
 <playlist id="playlist0">
  <property name="kdenlive:audio_track">1</property>
  <blank length="00:00:05.067"/>
  <entry in="00:00:00.000" out="00:00:13.033" producer="chain0">
   <property name="kdenlive:id">16</property>
  </entry>
  <blank length="00:00:13.067"/>
  <entry in="00:00:00.000" out="00:00:13.033" producer="chain0">
   <property name="kdenlive:id">16</property>
  </entry>
 </playlist>
 <playlist id="playlist1">
  <property name="kdenlive:audio_track">1</property>
 </playlist>
 <tractor id="tractor0" in="00:00:00.000" out="00:00:44.233">
  <property name="kdenlive:audio_track">1</property>
  <property name="kdenlive:trackheight">84</property>
  <property name="kdenlive:timeline_active">1</property>
  <property name="kdenlive:collapsed">0</property>
  <property name="kdenlive:thumbs_format"/>
  <property name="kdenlive:audio_rec"/>
  <track hide="video" producer="playlist0"/>
  <track hide="video" producer="playlist1"/>
  <filter id="filter0">
   <property name="window">75</property>
   <property name="max_gain">20dB</property>
   <property name="channel_mask">-1</property>
   <property name="mlt_service">volume</property>
   <property name="internal_added">237</property>
   <property name="disable">1</property>
  </filter>
  <filter id="filter1">
   <property name="channel">-1</property>
   <property name="mlt_service">panner</property>
   <property name="internal_added">237</property>
   <property name="start">0.5</property>
   <property name="disable">1</property>
  </filter>
  <filter id="filter2">
   <property name="iec_scale">0</property>
   <property name="prefix">meta.media.audio_level.</property>
   <property name="mlt_service">audiolevel</property>
   <property name="internal_added">237</property>
   <property name="dbpeak">1</property>
   <property name="disable">1</property>
  </filter>
 </tractor>
 <chain id="chain1" out="00:04:59.067">
  <property name="length">8973</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2489560/Downloads/AMBRurl_Campagne la nuit 4 (ID 1880)_LaSonotheque.fr.wav</property>
  <property name="mlt_service">avformat-novalidate</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">15</property>
  <property name="kdenlive:control_uuid">{f9510d91-34e7-46ee-8894-0eebd329b011}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">86142608</property>
  <property name="kdenlive:file_hash">cd76dee7108d820ffad229e01b6098ed</property>
  <property name="kdenlive:record_start_frame">-1</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:meta.extractor.Bitrate:">2304 kb/s</property>
  <property name="kdenlive:meta.extractor.Copyright:">CC0 / WTFPL / Public domain</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s32</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">2</property>
  <property name="meta.media.0.codec.layout">independent</property>
  <property name="meta.media.0.codec.name">pcm_s24le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 24-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">2304000</property>
  <property name="meta.attr.comment.markup">Campaign at night 4</property>
  <property name="meta.attr.encoded_by.markup">BigSoundBank.com</property>
  <property name="meta.attr.originator_reference.markup">1880</property>
  <property name="meta.attr.date.markup">2020-05-06</property>
  <property name="meta.attr.time_reference.markup">0</property>
  <property name="meta.attr.coding_history.markup">A=PCM,F=48000,W=24,M=stereo</property>
  <property name="meta.attr.copyright.markup">CC0 / WTFPL / Public domain</property>
  <property name="meta.attr.IKEY.markup">ambiance,campagne,exterieur,insecte,nature,nuit,atmosphere,soundscape,insect,chant,countryside,campaign,rural,nocturne,vent,wind,perche</property>
  <property name="meta.attr.IARL.markup">48.481879,0.964994</property>
  <property name="xml">was here</property>
  <property name="mute_on_pause">0</property>
  <property name="set.test_audio">0</property>
  <property name="set.test_image">1</property>
 </chain>
 <playlist id="playlist2">
  <property name="kdenlive:audio_track">1</property>
  <blank length="00:00:38.600"/>
  <entry in="00:04:00.533" out="00:04:26.900" producer="chain1">
   <property name="kdenlive:id">15</property>
  </entry>
 </playlist>
 <playlist id="playlist3">
  <property name="kdenlive:audio_track">1</property>
 </playlist>
 <tractor id="tractor1" in="00:00:00.000" out="00:01:04.967">
  <property name="kdenlive:audio_track">1</property>
  <property name="kdenlive:trackheight">84</property>
  <property name="kdenlive:timeline_active">1</property>
  <property name="kdenlive:collapsed">0</property>
  <property name="kdenlive:thumbs_format"/>
  <property name="kdenlive:audio_rec"/>
  <track hide="video" producer="playlist2"/>
  <track hide="video" producer="playlist3"/>
  <filter id="filter3">
   <property name="window">75</property>
   <property name="max_gain">20dB</property>
   <property name="channel_mask">-1</property>
   <property name="mlt_service">volume</property>
   <property name="internal_added">237</property>
   <property name="disable">1</property>
  </filter>
  <filter id="filter4">
   <property name="channel">-1</property>
   <property name="mlt_service">panner</property>
   <property name="internal_added">237</property>
   <property name="start">0.5</property>
   <property name="disable">1</property>
  </filter>
  <filter id="filter5">
   <property name="iec_scale">0</property>
   <property name="prefix">meta.media.audio_level.</property>
   <property name="mlt_service">audiolevel</property>
   <property name="internal_added">237</property>
   <property name="dbpeak">1</property>
   <property name="disable">1</property>
  </filter>
 </tractor>
 <chain id="chain2" out="00:01:37.400">
  <property name="length">2923</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2489560/Downloads/AMBFarm_Troupeau de 300 moutons 2 (ID 2972)_LaSonotheque.fr.wav</property>
  <property name="mlt_service">avformat-novalidate</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">14</property>
  <property name="kdenlive:control_uuid">{210425af-3019-4f64-9880-4a2fdc95131d}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">28062526</property>
  <property name="kdenlive:file_hash">6563f52ff4e715fa79eaad6ea0705bea</property>
  <property name="kdenlive:record_start_frame">-1</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:meta.extractor.Bitrate:">2304 kb/s</property>
  <property name="kdenlive:meta.extractor.Copyright:">CC0 / WTFPL / Public domain</property>
  <property name="kdenlive:monitorPosition">0</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s32</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">2</property>
  <property name="meta.media.0.codec.layout">independent</property>
  <property name="meta.media.0.codec.name">pcm_s24le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 24-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">2304000</property>
  <property name="meta.attr.comment.markup">Herd of 300 sheep 2</property>
  <property name="meta.attr.encoded_by.markup">BigSoundBank.com</property>
  <property name="meta.attr.originator_reference.markup">2972</property>
  <property name="meta.attr.date.markup">2023-06-01</property>
  <property name="meta.attr.time_reference.markup">0</property>
  <property name="meta.attr.coding_history.markup">A=PCM,F=48000,W=24,M=stereo</property>
  <property name="meta.attr.copyright.markup">CC0 / WTFPL / Public domain</property>
  <property name="meta.attr.IKEY.markup">chevre,bell,goat,cloche,animal,troupeau,bouc,ferme,farm,sonner,ambiance,soundscape,flock,herd,sheep,mouton</property>
  <property name="xml">was here</property>
  <property name="mute_on_pause">0</property>
  <property name="set.test_audio">0</property>
  <property name="set.test_image">1</property>
 </chain>
 <playlist id="playlist4">
  <property name="kdenlive:audio_track">1</property>
  <blank length="00:00:11.700"/>
  <entry in="00:00:40.467" out="00:00:49.500" producer="chain2">
   <property name="kdenlive:id">14</property>
  </entry>
 </playlist>
 <playlist id="playlist5">
  <property name="kdenlive:audio_track">1</property>
 </playlist>
 <tractor id="tractor2" in="00:00:00.000" out="00:00:20.733">
  <property name="kdenlive:audio_track">1</property>
  <property name="kdenlive:trackheight">84</property>
  <property name="kdenlive:timeline_active">1</property>
  <property name="kdenlive:collapsed">0</property>
  <property name="kdenlive:thumbs_format"/>
  <property name="kdenlive:audio_rec"/>
  <track hide="video" producer="playlist4"/>
  <track hide="video" producer="playlist5"/>
  <filter id="filter6">
   <property name="window">75</property>
   <property name="max_gain">20dB</property>
   <property name="level">4.45926</property>
   <property name="channel_mask">-1</property>
   <property name="mlt_service">volume</property>
   <property name="internal_added">237</property>
   <property name="disable">0</property>
  </filter>
  <filter id="filter7">
   <property name="channel">-1</property>
   <property name="mlt_service">panner</property>
   <property name="internal_added">237</property>
   <property name="start">0.5</property>
   <property name="disable">1</property>
  </filter>
  <filter id="filter8">
   <property name="iec_scale">0</property>
   <property name="prefix">meta.media.audio_level.</property>
   <property name="mlt_service">audiolevel</property>
   <property name="internal_added">237</property>
   <property name="dbpeak">1</property>
   <property name="disable">1</property>
  </filter>
 </tractor>
 <chain id="chain3" out="00:00:09.033">
  <property name="length">272</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2489560/Downloads/MUSCInst_Bol tibetain frappe 3 (ID 2554)_LaSonotheque.fr.wav</property>
  <property name="mlt_service">avformat-novalidate</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">13</property>
  <property name="kdenlive:control_uuid">{11c022c6-f1a7-45a8-b4a4-9bb70dd9e079}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">1308008</property>
  <property name="kdenlive:file_hash">937582b9fa8110fe667bef9e70bba6ed</property>
  <property name="kdenlive:record_start_frame">-1</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:meta.extractor.Bitrate:">1152 kb/s</property>
  <property name="kdenlive:meta.extractor.Copyright:">CC0 / WTFPL / Public domain</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s32</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">1</property>
  <property name="meta.media.0.codec.layout">mono</property>
  <property name="meta.media.0.codec.name">pcm_s24le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 24-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">1152000</property>
  <property name="meta.attr.comment.markup">Tibetan bowl struck 3</property>
  <property name="meta.attr.encoded_by.markup">BigSoundBank.com</property>
  <property name="meta.attr.originator_reference.markup">2554</property>
  <property name="meta.attr.date.markup">2022-02-13</property>
  <property name="meta.attr.time_reference.markup">0</property>
  <property name="meta.attr.coding_history.markup">A=PCM,F=48000,W=24,M=mono</property>
  <property name="meta.attr.copyright.markup">CC0 / WTFPL / Public domain</property>
  <property name="meta.attr.IKEY.markup">bol,tibetain,tibet,instrument,musique,chantant,chanter,tibetan,bowl,sing,singing,music,zen,frapper,buddhist,bouddhiste,tintement,meditation,relaxation,bouddhique,bouddhisme</property>
  <property name="xml">was here</property>
  <property name="mute_on_pause">0</property>
  <property name="set.test_audio">0</property>
  <property name="set.test_image">1</property>
 </chain>
 <playlist id="playlist6">
  <property name="kdenlive:audio_track">1</property>
  <entry in="00:00:00.000" out="00:00:09.033" producer="chain3">
   <property name="kdenlive:id">13</property>
  </entry>
  <entry in="00:00:00.000" out="00:00:09.033" producer="chain3">
   <property name="kdenlive:id">13</property>
  </entry>
  <entry in="00:00:00.000" out="00:00:09.033" producer="chain3">
   <property name="kdenlive:id">13</property>
  </entry>
  <entry in="00:00:00.000" out="00:00:09.033" producer="chain3">
   <property name="kdenlive:id">13</property>
  </entry>
  <entry in="00:00:00.000" out="00:00:09.033" producer="chain3">
   <property name="kdenlive:id">13</property>
  </entry>
  <entry in="00:00:00.000" out="00:00:09.033" producer="chain3">
   <property name="kdenlive:id">13</property>
  </entry>
  <entry in="00:00:00.000" out="00:00:09.033" producer="chain3">
   <property name="kdenlive:id">13</property>
  </entry>
 </playlist>
 <playlist id="playlist7">
  <property name="kdenlive:audio_track">1</property>
 </playlist>
 <tractor id="tractor3" in="00:00:00.000" out="00:01:03.433">
  <property name="kdenlive:audio_track">1</property>
  <property name="kdenlive:trackheight">84</property>
  <property name="kdenlive:timeline_active">1</property>
  <property name="kdenlive:collapsed">0</property>
  <property name="kdenlive:thumbs_format"/>
  <property name="kdenlive:audio_rec"/>
  <track hide="video" producer="playlist6"/>
  <track hide="video" producer="playlist7"/>
  <filter id="filter9">
   <property name="window">75</property>
   <property name="max_gain">20dB</property>
   <property name="level">0.065873</property>
   <property name="channel_mask">-1</property>
   <property name="mlt_service">volume</property>
   <property name="internal_added">237</property>
   <property name="disable">0</property>
  </filter>
  <filter id="filter10">
   <property name="channel">-1</property>
   <property name="mlt_service">panner</property>
   <property name="internal_added">237</property>
   <property name="start">0.5</property>
   <property name="disable">1</property>
  </filter>
  <filter id="filter11">
   <property name="iec_scale">0</property>
   <property name="prefix">meta.media.audio_level.</property>
   <property name="mlt_service">audiolevel</property>
   <property name="internal_added">237</property>
   <property name="dbpeak">1</property>
   <property name="disable">1</property>
  </filter>
 </tractor>
 <chain id="chain4" out="00:04:05.200">
  <property name="length">7357</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2489560/Downloads/AMBBird_Reveil des oiseaux 3 (ID 0999)_LaSonotheque.fr.wav</property>
  <property name="mlt_service">avformat-novalidate</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">12</property>
  <property name="kdenlive:control_uuid">{626d515d-f68f-4b3e-9bb1-7d354efea881}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">47088360</property>
  <property name="kdenlive:file_hash">2671064b5e80e6a2029d407a9b14f376</property>
  <property name="kdenlive:record_start_frame">-1</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:meta.extractor.Bitrate:">1536 kb/s</property>
  <property name="kdenlive:meta.extractor.Copyright:">CC0 / WTFPL / Public domain</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s16</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">2</property>
  <property name="meta.media.0.codec.layout">independent</property>
  <property name="meta.media.0.codec.name">pcm_s16le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 16-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">1536000</property>
  <property name="meta.attr.comment.markup">Wake birds 3</property>
  <property name="meta.attr.encoded_by.markup">BigSoundBank.com</property>
  <property name="meta.attr.originator_reference.markup">0999</property>
  <property name="meta.attr.date.markup">2018-04-24</property>
  <property name="meta.attr.time_reference.markup">0</property>
  <property name="meta.attr.coding_history.markup">A=PCM,F=48000,W=16,M=stereo</property>
  <property name="meta.attr.copyright.markup">CC0 / WTFPL / Public domain</property>
  <property name="meta.attr.IKEY.markup">ambiance,ambient,animal,atmosphere,bird,campagne,countryside,environment,nature,oiseau,printemps,sauvage,savage,soundscape,chirping,chanter,chant,sing,campaign,morning,piailler,rural,chirp,eveiller,eveil,reveiller,matin,morning,morn,morrow,perche,rossignol,nightingale</property>
  <property name="xml">was here</property>
  <property name="mute_on_pause">0</property>
  <property name="set.test_audio">0</property>
  <property name="set.test_image">1</property>
 </chain>
 <playlist id="playlist8">
  <property name="kdenlive:audio_track">1</property>
  <entry in="00:02:21.567" out="00:02:33.467" producer="chain4">
   <property name="kdenlive:id">12</property>
  </entry>
  <blank length="00:00:12.033"/>
  <entry in="00:02:21.567" out="00:02:44.500" producer="chain4">
   <property name="kdenlive:id">12</property>
  </entry>
 </playlist>
 <playlist id="playlist9">
  <property name="kdenlive:audio_track">1</property>
 </playlist>
 <tractor id="tractor4" in="00:00:00.000" out="00:00:46.900">
  <property name="kdenlive:audio_track">1</property>
  <property name="kdenlive:trackheight">84</property>
  <property name="kdenlive:timeline_active">1</property>
  <property name="kdenlive:collapsed">0</property>
  <property name="kdenlive:thumbs_format"/>
  <property name="kdenlive:audio_rec"/>
  <track hide="video" producer="playlist8"/>
  <track hide="video" producer="playlist9"/>
  <filter id="filter12">
   <property name="window">75</property>
   <property name="max_gain">20dB</property>
   <property name="level">0.0989663</property>
   <property name="channel_mask">-1</property>
   <property name="mlt_service">volume</property>
   <property name="internal_added">237</property>
   <property name="disable">0</property>
  </filter>
  <filter id="filter13">
   <property name="channel">-1</property>
   <property name="mlt_service">panner</property>
   <property name="internal_added">237</property>
   <property name="start">0.5</property>
   <property name="disable">1</property>
  </filter>
  <filter id="filter14">
   <property name="iec_scale">0</property>
   <property name="prefix">meta.media.audio_level.</property>
   <property name="mlt_service">audiolevel</property>
   <property name="internal_added">237</property>
   <property name="dbpeak">1</property>
   <property name="disable">1</property>
  </filter>
 </tractor>
 <chain id="chain5" out="00:03:00.067">
  <property name="length">5403</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2489560/Downloads/WINDVege_Vent dans un arbuste (ID 0907)_LaSonotheque.fr.wav</property>
  <property name="mlt_service">avformat-novalidate</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">11</property>
  <property name="kdenlive:control_uuid">{c97dd924-0c93-4bf4-b87a-bb7dd832b7b0}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">34582104</property>
  <property name="kdenlive:file_hash">30f3f1c1e709f12efcf47b0ae10dac29</property>
  <property name="kdenlive:record_start_frame">-1</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:meta.extractor.Bitrate:">1536 kb/s</property>
  <property name="kdenlive:meta.extractor.Copyright:">CC0 / WTFPL / Public domain</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s16</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">2</property>
  <property name="meta.media.0.codec.layout">independent</property>
  <property name="meta.media.0.codec.name">pcm_s16le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 16-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">1536000</property>
  <property name="meta.attr.comment.markup">Wind in shrub</property>
  <property name="meta.attr.encoded_by.markup">BigSoundBank.com</property>
  <property name="meta.attr.originator_reference.markup">0907</property>
  <property name="meta.attr.date.markup">2015-04-19</property>
  <property name="meta.attr.time_reference.markup">0</property>
  <property name="meta.attr.coding_history.markup">A=PCM,F=48000,W=16,M=stereo</property>
  <property name="meta.attr.copyright.markup">CC0 / WTFPL / Public domain</property>
  <property name="meta.attr.IKEY.markup">vent,wind,arbuste,shrub,ambiance,nature,atmosphere,soundscape,gust,blowing,blow,souffler</property>
  <property name="xml">was here</property>
  <property name="mute_on_pause">0</property>
  <property name="set.test_audio">0</property>
  <property name="set.test_image">1</property>
 </chain>
 <playlist id="playlist10">
  <property name="kdenlive:audio_track">1</property>
  <entry in="00:01:44.933" out="00:02:49.933" producer="chain5">
   <property name="kdenlive:id">11</property>
  </entry>
 </playlist>
 <playlist id="playlist11">
  <property name="kdenlive:audio_track">1</property>
 </playlist>
 <tractor id="tractor5" in="00:00:00.000" out="00:01:05.000">
  <property name="kdenlive:audio_track">1</property>
  <property name="kdenlive:trackheight">84</property>
  <property name="kdenlive:timeline_active">1</property>
  <property name="kdenlive:collapsed">0</property>
  <property name="kdenlive:thumbs_format"/>
  <property name="kdenlive:audio_rec"/>
  <track hide="video" producer="playlist10"/>
  <track hide="video" producer="playlist11"/>
  <filter id="filter15">
   <property name="window">75</property>
   <property name="max_gain">20dB</property>
   <property name="level">0.194102</property>
   <property name="channel_mask">-1</property>
   <property name="mlt_service">volume</property>
   <property name="internal_added">237</property>
   <property name="disable">0</property>
  </filter>
  <filter id="filter16">
   <property name="channel">-1</property>
   <property name="mlt_service">panner</property>
   <property name="internal_added">237</property>
   <property name="start">0.5</property>
   <property name="disable">1</property>
  </filter>
  <filter id="filter17">
   <property name="iec_scale">0</property>
   <property name="prefix">meta.media.audio_level.</property>
   <property name="mlt_service">audiolevel</property>
   <property name="internal_added">237</property>
   <property name="dbpeak">1</property>
   <property name="disable">1</property>
  </filter>
 </tractor>
 <chain id="chain6" out="00:00:03.067">
  <property name="length">93</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2489560/Downloads/BIRDSong_Rouge gorge 4 (ID 1670)_LaSonotheque.fr.wav</property>
  <property name="mlt_service">avformat-novalidate</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">10</property>
  <property name="kdenlive:control_uuid">{6b5fb92f-4db8-4a6c-b2d0-edf30f444a41}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">449752</property>
  <property name="kdenlive:file_hash">086d7b3c441526355263c2be0bb0d1dd</property>
  <property name="kdenlive:record_start_frame">-1</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:meta.extractor.Bitrate:">1152 kb/s</property>
  <property name="kdenlive:meta.extractor.Copyright:">CC0 / WTFPL / Public domain</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s32</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">1</property>
  <property name="meta.media.0.codec.layout">mono</property>
  <property name="meta.media.0.codec.name">pcm_s24le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 24-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">1152000</property>
  <property name="meta.attr.comment.markup">Robin 4</property>
  <property name="meta.attr.encoded_by.markup">BigSoundBank.com</property>
  <property name="meta.attr.originator_reference.markup">1670</property>
  <property name="meta.attr.date.markup">2019-10-21</property>
  <property name="meta.attr.time_reference.markup">0</property>
  <property name="meta.attr.coding_history.markup">A=PCM,F=48000,W=24,M=mono</property>
  <property name="meta.attr.copyright.markup">CC0 / WTFPL / Public domain</property>
  <property name="meta.attr.IKEY.markup">oiseau,bird,robin,rouge,gorge,jardin,garden,merle,americain,redbreast,animal,chirping,chanter,oviparite,ovipare,oviparity,oviparous,chant,chanter,cri,crier,sauvage,wild</property>
  <property name="xml">was here</property>
  <property name="mute_on_pause">0</property>
  <property name="set.test_audio">0</property>
  <property name="set.test_image">1</property>
 </chain>
 <playlist id="playlist12">
  <property name="kdenlive:audio_track">1</property>
  <blank length="00:00:05.067"/>
  <entry in="00:00:00.000" out="00:00:03.067" producer="chain6">
   <property name="kdenlive:id">10</property>
  </entry>
  <blank length="00:00:09.500"/>
  <entry in="00:00:00.000" out="00:00:03.067" producer="chain6">
   <property name="kdenlive:id">10</property>
  </entry>
  <blank length="00:00:12.733"/>
  <entry in="00:00:00.000" out="00:00:03.067" producer="chain6">
   <property name="kdenlive:id">10</property>
  </entry>
  <blank length="00:00:11.300"/>
  <entry in="00:00:00.000" out="00:00:03.067" producer="chain6">
   <property name="kdenlive:id">10</property>
  </entry>
  <blank length="00:00:10.933"/>
  <entry in="00:00:00.000" out="00:00:03.067" producer="chain6">
   <property name="kdenlive:id">10</property>
  </entry>
 </playlist>
 <playlist id="playlist13">
  <property name="kdenlive:audio_track">1</property>
 </playlist>
 <tractor id="tractor6" in="00:00:00.000" out="00:01:05.000">
  <property name="kdenlive:audio_track">1</property>
  <property name="kdenlive:trackheight">84</property>
  <property name="kdenlive:timeline_active">1</property>
  <property name="kdenlive:collapsed">0</property>
  <property name="kdenlive:thumbs_format"/>
  <property name="kdenlive:audio_rec"/>
  <track hide="video" producer="playlist12"/>
  <track hide="video" producer="playlist13"/>
  <filter id="filter18">
   <property name="window">75</property>
   <property name="max_gain">20dB</property>
   <property name="level">0.290113</property>
   <property name="channel_mask">-1</property>
   <property name="mlt_service">volume</property>
   <property name="internal_added">237</property>
   <property name="disable">0</property>
  </filter>
  <filter id="filter19">
   <property name="channel">-1</property>
   <property name="mlt_service">panner</property>
   <property name="internal_added">237</property>
   <property name="start">0.5</property>
   <property name="disable">1</property>
  </filter>
  <filter id="filter20">
   <property name="iec_scale">0</property>
   <property name="prefix">meta.media.audio_level.</property>
   <property name="mlt_service">audiolevel</property>
   <property name="internal_added">237</property>
   <property name="dbpeak">1</property>
   <property name="disable">1</property>
  </filter>
 </tractor>
 <chain id="chain7" out="00:01:29.400">
  <property name="length">2683</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2489560/Downloads/WINDDsgn_Vent (ID 0595)_LaSonotheque.fr (1).wav</property>
  <property name="mlt_service">avformat-novalidate</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">9</property>
  <property name="kdenlive:control_uuid">{1cc59805-6f60-4ec9-96f1-def812970e40}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">8586182</property>
  <property name="kdenlive:file_hash">c3651a89e30511470b7f05af137b16a2</property>
  <property name="kdenlive:record_start_frame">-1</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:meta.extractor.Bitrate:">768 kb/s</property>
  <property name="kdenlive:meta.extractor.Copyright:">CC0 / WTFPL / Public domain</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s16</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">1</property>
  <property name="meta.media.0.codec.layout">mono</property>
  <property name="meta.media.0.codec.name">pcm_s16le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 16-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">768000</property>
  <property name="meta.attr.comment.markup">Wind</property>
  <property name="meta.attr.encoded_by.markup">BigSoundBank.com</property>
  <property name="meta.attr.originator_reference.markup">0595</property>
  <property name="meta.attr.date.markup">2013-01-05</property>
  <property name="meta.attr.time_reference.markup">0</property>
  <property name="meta.attr.coding_history.markup">A=PCM,F=48000,W=16,M=mono</property>
  <property name="meta.attr.copyright.markup">CC0 / WTFPL / Public domain</property>
  <property name="meta.attr.IKEY.markup">bruitage,foley,souffle,technique,vent,wind,gust,blowing,blow,souffler,siffler,sifflement,whistles,whistle</property>
  <property name="xml">was here</property>
  <property name="mute_on_pause">0</property>
  <property name="set.test_audio">0</property>
  <property name="set.test_image">1</property>
 </chain>
 <playlist id="playlist14">
  <property name="kdenlive:audio_track">1</property>
  <entry in="00:00:00.000" out="00:01:05.000" producer="chain7">
   <property name="kdenlive:id">9</property>
  </entry>
 </playlist>
 <playlist id="playlist15">
  <property name="kdenlive:audio_track">1</property>
 </playlist>
 <tractor id="tractor7" in="00:00:00.000" out="00:01:05.000">
  <property name="kdenlive:audio_track">1</property>
  <property name="kdenlive:trackheight">84</property>
  <property name="kdenlive:timeline_active">1</property>
  <property name="kdenlive:collapsed">0</property>
  <property name="kdenlive:thumbs_format"/>
  <property name="kdenlive:audio_rec"/>
  <track hide="video" producer="playlist14"/>
  <track hide="video" producer="playlist15"/>
  <filter id="filter21">
   <property name="window">75</property>
   <property name="max_gain">20dB</property>
   <property name="level">0.0989663</property>
   <property name="channel_mask">-1</property>
   <property name="mlt_service">volume</property>
   <property name="internal_added">237</property>
   <property name="disable">0</property>
  </filter>
  <filter id="filter22">
   <property name="channel">-1</property>
   <property name="mlt_service">panner</property>
   <property name="internal_added">237</property>
   <property name="start">0.5</property>
   <property name="disable">1</property>
  </filter>
  <filter id="filter23">
   <property name="iec_scale">0</property>
   <property name="prefix">meta.media.audio_level.</property>
   <property name="mlt_service">audiolevel</property>
   <property name="internal_added">237</property>
   <property name="dbpeak">1</property>
   <property name="disable">1</property>
  </filter>
 </tractor>
 <producer id="producer1" in="00:00:00.000" out="00:01:05.700">
  <property name="length">1972</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2489560/Downloads/kanenori-mountain-5678172_1920.jpg</property>
  <property name="ttl">25</property>
  <property name="aspect_ratio">1</property>
  <property name="meta.media.progressive">1</property>
  <property name="seekable">1</property>
  <property name="format">1</property>
  <property name="meta.media.width">1920</property>
  <property name="meta.media.height">1280</property>
  <property name="mlt_service">qimage</property>
  <property name="kdenlive:duration">00:00:05:00</property>
  <property name="xml">was here</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">6</property>
  <property name="kdenlive:control_uuid">{93439c27-db45-42cd-96d3-2ae2956ca26a}</property>
  <property name="kdenlive:clip_type">2</property>
  <property name="kdenlive:file_size">680179</property>
  <property name="kdenlive:file_hash">4a59e3adf048c4eaeca4aa16d364adc7</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:monitorPosition">149</property>
 </producer>
 <playlist id="playlist16">
  <entry in="00:00:00.000" out="00:01:05.000" producer="producer1">
   <property name="kdenlive:id">6</property>
  </entry>
 </playlist>
 <playlist id="playlist17"/>
 <tractor id="tractor8" in="00:00:00.000" out="00:01:05.000">
  <property name="kdenlive:trackheight">84</property>
  <property name="kdenlive:timeline_active">1</property>
  <property name="kdenlive:collapsed">0</property>
  <property name="kdenlive:thumbs_format"/>
  <property name="kdenlive:audio_rec"/>
  <track hide="audio" producer="playlist16"/>
  <track hide="audio" producer="playlist17"/>
 </tractor>
 <playlist id="playlist18"/>
 <playlist id="playlist19"/>
 <tractor id="tractor9" in="00:00:00.000">
  <property name="kdenlive:trackheight">84</property>
  <property name="kdenlive:timeline_active">1</property>
  <property name="kdenlive:collapsed">0</property>
  <property name="kdenlive:thumbs_format"/>
  <property name="kdenlive:audio_rec"/>
  <track hide="audio" producer="playlist18"/>
  <track hide="audio" producer="playlist19"/>
 </tractor>
 <tractor id="{91e5eb31-9eec-4c68-a20b-793717e49a30}" in="00:00:00.000" out="00:01:05.000">
  <property name="kdenlive:uuid">{91e5eb31-9eec-4c68-a20b-793717e49a30}</property>
  <property name="kdenlive:clipname">Séquence 1</property>
  <property name="kdenlive:sequenceproperties.hasAudio">1</property>
  <property name="kdenlive:sequenceproperties.hasVideo">1</property>
  <property name="kdenlive:sequenceproperties.activeTrack">4</property>
  <property name="kdenlive:sequenceproperties.tracksCount">10</property>
  <property name="kdenlive:sequenceproperties.documentuuid">{91e5eb31-9eec-4c68-a20b-793717e49a30}</property>
  <property name="kdenlive:control_uuid">{91e5eb31-9eec-4c68-a20b-793717e49a30}</property>
  <property name="kdenlive:duration">00:01:05.033</property>
  <property name="kdenlive:maxduration">1951</property>
  <property name="kdenlive:producer_type">17</property>
  <property name="kdenlive:id">3</property>
  <property name="kdenlive:clip_type">0</property>
  <property name="kdenlive:file_size">0</property>
  <property name="kdenlive:folderid">2</property>
  <property name="kdenlive:sequenceproperties.audioTarget">7</property>
  <property name="kdenlive:sequenceproperties.disablepreview">0</property>
  <property name="kdenlive:sequenceproperties.position">1084</property>
  <property name="kdenlive:sequenceproperties.scrollPos">0</property>
  <property name="kdenlive:sequenceproperties.tracks">10</property>
  <property name="kdenlive:sequenceproperties.verticalzoom">1</property>
  <property name="kdenlive:sequenceproperties.videoTarget">8</property>
  <property name="kdenlive:sequenceproperties.zonein">0</property>
  <property name="kdenlive:sequenceproperties.zoneout">75</property>
  <property name="kdenlive:sequenceproperties.zoom">8</property>
  <property name="kdenlive:sequenceproperties.groups">[
]
</property>
  <property name="kdenlive:sequenceproperties.guides">[
]
</property>
  <track producer="producer0"/>
  <track producer="tractor0"/>
  <track producer="tractor1"/>
  <track producer="tractor2"/>
  <track producer="tractor3"/>
  <track producer="tractor4"/>
  <track producer="tractor5"/>
  <track producer="tractor6"/>
  <track producer="tractor7"/>
  <track producer="tractor8"/>
  <track producer="tractor9"/>
  <transition id="transition0">
   <property name="a_track">0</property>
   <property name="b_track">1</property>
   <property name="duck_threshold">0</property>
   <property name="duck_attenuation">-12</property>
   <property name="duck_level">0</property>
   <property name="duck_fade_in">1500</property>
   <property name="duck_fade_out">250</property>
   <property name="prefix"/>
   <property name="mlt_service">mix</property>
   <property name="kdenlive_id">mix</property>
   <property name="internal_added">237</property>
   <property name="always_active">1</property>
   <property name="accepts_blanks">1</property>
   <property name="sum">1</property>
  </transition>
  <transition id="transition1">
   <property name="a_track">0</property>
   <property name="b_track">2</property>
   <property name="duck_threshold">0</property>
   <property name="duck_attenuation">-12</property>
   <property name="duck_level">0</property>
   <property name="duck_fade_in">1500</property>
   <property name="duck_fade_out">250</property>
   <property name="prefix"/>
   <property name="mlt_service">mix</property>
   <property name="kdenlive_id">mix</property>
   <property name="internal_added">237</property>
   <property name="always_active">1</property>
   <property name="accepts_blanks">1</property>
   <property name="sum">1</property>
  </transition>
  <transition id="transition2">
   <property name="a_track">0</property>
   <property name="b_track">3</property>
   <property name="duck_threshold">0</property>
   <property name="duck_attenuation">-12</property>
   <property name="duck_level">0</property>
   <property name="duck_fade_in">1500</property>
   <property name="duck_fade_out">250</property>
   <property name="prefix"/>
   <property name="mlt_service">mix</property>
   <property name="kdenlive_id">mix</property>
   <property name="internal_added">237</property>
   <property name="always_active">1</property>
   <property name="accepts_blanks">1</property>
   <property name="sum">1</property>
  </transition>
  <transition id="transition3">
   <property name="a_track">0</property>
   <property name="b_track">4</property>
   <property name="duck_threshold">0</property>
   <property name="duck_attenuation">-12</property>
   <property name="duck_level">0</property>
   <property name="duck_fade_in">1500</property>
   <property name="duck_fade_out">250</property>
   <property name="prefix"/>
   <property name="mlt_service">mix</property>
   <property name="kdenlive_id">mix</property>
   <property name="internal_added">237</property>
   <property name="always_active">1</property>
   <property name="accepts_blanks">1</property>
   <property name="sum">1</property>
  </transition>
  <transition id="transition4">
   <property name="a_track">0</property>
   <property name="b_track">5</property>
   <property name="duck_threshold">0</property>
   <property name="duck_attenuation">-12</property>
   <property name="duck_level">0</property>
   <property name="duck_fade_in">1500</property>
   <property name="duck_fade_out">250</property>
   <property name="prefix"/>
   <property name="mlt_service">mix</property>
   <property name="kdenlive_id">mix</property>
   <property name="internal_added">237</property>
   <property name="always_active">1</property>
   <property name="accepts_blanks">1</property>
   <property name="sum">1</property>
  </transition>
  <transition id="transition5">
   <property name="a_track">0</property>
   <property name="b_track">6</property>
   <property name="duck_threshold">0</property>
   <property name="duck_attenuation">-12</property>
   <property name="duck_level">0</property>
   <property name="duck_fade_in">1500</property>
   <property name="duck_fade_out">250</property>
   <property name="prefix"/>
   <property name="mlt_service">mix</property>
   <property name="kdenlive_id">mix</property>
   <property name="internal_added">237</property>
   <property name="always_active">1</property>
   <property name="accepts_blanks">1</property>
   <property name="sum">1</property>
  </transition>
  <transition id="transition6">
   <property name="a_track">0</property>
   <property name="b_track">7</property>
   <property name="duck_threshold">0</property>
   <property name="duck_attenuation">-12</property>
   <property name="duck_level">0</property>
   <property name="duck_fade_in">1500</property>
   <property name="duck_fade_out">250</property>
   <property name="prefix"/>
   <property name="mlt_service">mix</property>
   <property name="kdenlive_id">mix</property>
   <property name="internal_added">237</property>
   <property name="always_active">1</property>
   <property name="accepts_blanks">1</property>
   <property name="sum">1</property>
  </transition>
  <transition id="transition7">
   <property name="a_track">0</property>
   <property name="b_track">8</property>
   <property name="duck_threshold">0</property>
   <property name="duck_attenuation">-12</property>
   <property name="duck_level">0</property>
   <property name="duck_fade_in">1500</property>
   <property name="duck_fade_out">250</property>
   <property name="prefix"/>
   <property name="mlt_service">mix</property>
   <property name="kdenlive_id">mix</property>
   <property name="internal_added">237</property>
   <property name="always_active">1</property>
   <property name="accepts_blanks">1</property>
   <property name="sum">1</property>
  </transition>
  <transition id="transition8">
   <property name="a_track">0</property>
   <property name="b_track">9</property>
   <property name="compositing">0</property>
   <property name="distort">0</property>
   <property name="rotate_center">0</property>
   <property name="mlt_service">qtblend</property>
   <property name="kdenlive_id">qtblend</property>
   <property name="internal_added">237</property>
   <property name="always_active">1</property>
  </transition>
  <transition id="transition9">
   <property name="a_track">0</property>
   <property name="b_track">10</property>
   <property name="compositing">0</property>
   <property name="distort">0</property>
   <property name="rotate_center">0</property>
   <property name="mlt_service">qtblend</property>
   <property name="kdenlive_id">qtblend</property>
   <property name="internal_added">237</property>
   <property name="always_active">1</property>
  </transition>
  <filter id="filter24">
   <property name="window">75</property>
   <property name="max_gain">20dB</property>
   <property name="level">-1.99139</property>
   <property name="channel_mask">-1</property>
   <property name="mlt_service">volume</property>
   <property name="internal_added">237</property>
   <property name="disable">0</property>
  </filter>
  <filter id="filter25">
   <property name="channel">-1</property>
   <property name="mlt_service">panner</property>
   <property name="internal_added">237</property>
   <property name="start">0.5</property>
   <property name="disable">1</property>
  </filter>
 </tractor>
 <chain id="chain8" out="00:01:29.400">
  <property name="length">2683</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2489560/Downloads/WINDDsgn_Vent (ID 0595)_LaSonotheque.fr (1).wav</property>
  <property name="mlt_service">avformat</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s16</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">1</property>
  <property name="meta.media.0.codec.layout">mono</property>
  <property name="meta.media.0.codec.name">pcm_s16le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 16-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">768000</property>
  <property name="meta.attr.comment.markup">Wind</property>
  <property name="meta.attr.encoded_by.markup">BigSoundBank.com</property>
  <property name="meta.attr.originator_reference.markup">0595</property>
  <property name="meta.attr.date.markup">2013-01-05</property>
  <property name="meta.attr.time_reference.markup">0</property>
  <property name="meta.attr.coding_history.markup">A=PCM,F=48000,W=16,M=mono</property>
  <property name="meta.attr.copyright.markup">CC0 / WTFPL / Public domain</property>
  <property name="meta.attr.IKEY.markup">bruitage,foley,souffle,technique,vent,wind,gust,blowing,blow,souffler,siffler,sifflement,whistles,whistle</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">9</property>
  <property name="kdenlive:control_uuid">{1cc59805-6f60-4ec9-96f1-def812970e40}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">8586182</property>
  <property name="kdenlive:file_hash">c3651a89e30511470b7f05af137b16a2</property>
  <property name="kdenlive:record_start_frame">-1</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:meta.extractor.Bitrate:">768 kb/s</property>
  <property name="kdenlive:meta.extractor.Copyright:">CC0 / WTFPL / Public domain</property>
  <property name="kdenlive:monitorPosition">2682</property>
 </chain>
 <chain id="chain9" out="00:00:03.067">
  <property name="length">93</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2489560/Downloads/BIRDSong_Rouge gorge 4 (ID 1670)_LaSonotheque.fr.wav</property>
  <property name="mlt_service">avformat</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s32</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">1</property>
  <property name="meta.media.0.codec.layout">mono</property>
  <property name="meta.media.0.codec.name">pcm_s24le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 24-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">1152000</property>
  <property name="meta.attr.comment.markup">Robin 4</property>
  <property name="meta.attr.encoded_by.markup">BigSoundBank.com</property>
  <property name="meta.attr.originator_reference.markup">1670</property>
  <property name="meta.attr.date.markup">2019-10-21</property>
  <property name="meta.attr.time_reference.markup">0</property>
  <property name="meta.attr.coding_history.markup">A=PCM,F=48000,W=24,M=mono</property>
  <property name="meta.attr.copyright.markup">CC0 / WTFPL / Public domain</property>
  <property name="meta.attr.IKEY.markup">oiseau,bird,robin,rouge,gorge,jardin,garden,merle,americain,redbreast,animal,chirping,chanter,oviparite,ovipare,oviparity,oviparous,chant,chanter,cri,crier,sauvage,wild</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">10</property>
  <property name="kdenlive:control_uuid">{6b5fb92f-4db8-4a6c-b2d0-edf30f444a41}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">449752</property>
  <property name="kdenlive:file_hash">086d7b3c441526355263c2be0bb0d1dd</property>
  <property name="kdenlive:record_start_frame">-1</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:meta.extractor.Bitrate:">1152 kb/s</property>
  <property name="kdenlive:meta.extractor.Copyright:">CC0 / WTFPL / Public domain</property>
  <property name="kdenlive:monitorPosition">92</property>
 </chain>
 <chain id="chain10" out="00:03:00.067">
  <property name="length">5403</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2489560/Downloads/WINDVege_Vent dans un arbuste (ID 0907)_LaSonotheque.fr.wav</property>
  <property name="mlt_service">avformat</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s16</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">2</property>
  <property name="meta.media.0.codec.layout">independent</property>
  <property name="meta.media.0.codec.name">pcm_s16le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 16-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">1536000</property>
  <property name="meta.attr.comment.markup">Wind in shrub</property>
  <property name="meta.attr.encoded_by.markup">BigSoundBank.com</property>
  <property name="meta.attr.originator_reference.markup">0907</property>
  <property name="meta.attr.date.markup">2015-04-19</property>
  <property name="meta.attr.time_reference.markup">0</property>
  <property name="meta.attr.coding_history.markup">A=PCM,F=48000,W=16,M=stereo</property>
  <property name="meta.attr.copyright.markup">CC0 / WTFPL / Public domain</property>
  <property name="meta.attr.IKEY.markup">vent,wind,arbuste,shrub,ambiance,nature,atmosphere,soundscape,gust,blowing,blow,souffler</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">11</property>
  <property name="kdenlive:control_uuid">{c97dd924-0c93-4bf4-b87a-bb7dd832b7b0}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">34582104</property>
  <property name="kdenlive:file_hash">30f3f1c1e709f12efcf47b0ae10dac29</property>
  <property name="kdenlive:record_start_frame">-1</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:meta.extractor.Bitrate:">1536 kb/s</property>
  <property name="kdenlive:meta.extractor.Copyright:">CC0 / WTFPL / Public domain</property>
  <property name="kdenlive:monitorPosition">0</property>
 </chain>
 <chain id="chain11" out="00:04:05.200">
  <property name="length">7357</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2489560/Downloads/AMBBird_Reveil des oiseaux 3 (ID 0999)_LaSonotheque.fr.wav</property>
  <property name="mlt_service">avformat</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s16</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">2</property>
  <property name="meta.media.0.codec.layout">independent</property>
  <property name="meta.media.0.codec.name">pcm_s16le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 16-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">1536000</property>
  <property name="meta.attr.comment.markup">Wake birds 3</property>
  <property name="meta.attr.encoded_by.markup">BigSoundBank.com</property>
  <property name="meta.attr.originator_reference.markup">0999</property>
  <property name="meta.attr.date.markup">2018-04-24</property>
  <property name="meta.attr.time_reference.markup">0</property>
  <property name="meta.attr.coding_history.markup">A=PCM,F=48000,W=16,M=stereo</property>
  <property name="meta.attr.copyright.markup">CC0 / WTFPL / Public domain</property>
  <property name="meta.attr.IKEY.markup">ambiance,ambient,animal,atmosphere,bird,campagne,countryside,environment,nature,oiseau,printemps,sauvage,savage,soundscape,chirping,chanter,chant,sing,campaign,morning,piailler,rural,chirp,eveiller,eveil,reveiller,matin,morning,morn,morrow,perche,rossignol,nightingale</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">12</property>
  <property name="kdenlive:control_uuid">{626d515d-f68f-4b3e-9bb1-7d354efea881}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">47088360</property>
  <property name="kdenlive:file_hash">2671064b5e80e6a2029d407a9b14f376</property>
  <property name="kdenlive:record_start_frame">-1</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:meta.extractor.Bitrate:">1536 kb/s</property>
  <property name="kdenlive:meta.extractor.Copyright:">CC0 / WTFPL / Public domain</property>
  <property name="kdenlive:monitorPosition">0</property>
 </chain>
 <chain id="chain12" out="00:00:09.033">
  <property name="length">272</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2489560/Downloads/MUSCInst_Bol tibetain frappe 3 (ID 2554)_LaSonotheque.fr.wav</property>
  <property name="mlt_service">avformat</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s32</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">1</property>
  <property name="meta.media.0.codec.layout">mono</property>
  <property name="meta.media.0.codec.name">pcm_s24le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 24-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">1152000</property>
  <property name="meta.attr.comment.markup">Tibetan bowl struck 3</property>
  <property name="meta.attr.encoded_by.markup">BigSoundBank.com</property>
  <property name="meta.attr.originator_reference.markup">2554</property>
  <property name="meta.attr.date.markup">2022-02-13</property>
  <property name="meta.attr.time_reference.markup">0</property>
  <property name="meta.attr.coding_history.markup">A=PCM,F=48000,W=24,M=mono</property>
  <property name="meta.attr.copyright.markup">CC0 / WTFPL / Public domain</property>
  <property name="meta.attr.IKEY.markup">bol,tibetain,tibet,instrument,musique,chantant,chanter,tibetan,bowl,sing,singing,music,zen,frapper,buddhist,bouddhiste,tintement,meditation,relaxation,bouddhique,bouddhisme</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">13</property>
  <property name="kdenlive:control_uuid">{11c022c6-f1a7-45a8-b4a4-9bb70dd9e079}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">1308008</property>
  <property name="kdenlive:file_hash">937582b9fa8110fe667bef9e70bba6ed</property>
  <property name="kdenlive:record_start_frame">-1</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:meta.extractor.Bitrate:">1152 kb/s</property>
  <property name="kdenlive:meta.extractor.Copyright:">CC0 / WTFPL / Public domain</property>
  <property name="kdenlive:monitorPosition">0</property>
 </chain>
 <chain id="chain13" out="00:01:37.400">
  <property name="length">2923</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2489560/Downloads/AMBFarm_Troupeau de 300 moutons 2 (ID 2972)_LaSonotheque.fr.wav</property>
  <property name="mlt_service">avformat</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s32</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">2</property>
  <property name="meta.media.0.codec.layout">independent</property>
  <property name="meta.media.0.codec.name">pcm_s24le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 24-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">2304000</property>
  <property name="meta.attr.comment.markup">Herd of 300 sheep 2</property>
  <property name="meta.attr.encoded_by.markup">BigSoundBank.com</property>
  <property name="meta.attr.originator_reference.markup">2972</property>
  <property name="meta.attr.date.markup">2023-06-01</property>
  <property name="meta.attr.time_reference.markup">0</property>
  <property name="meta.attr.coding_history.markup">A=PCM,F=48000,W=24,M=stereo</property>
  <property name="meta.attr.copyright.markup">CC0 / WTFPL / Public domain</property>
  <property name="meta.attr.IKEY.markup">chevre,bell,goat,cloche,animal,troupeau,bouc,ferme,farm,sonner,ambiance,soundscape,flock,herd,sheep,mouton</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">14</property>
  <property name="kdenlive:control_uuid">{210425af-3019-4f64-9880-4a2fdc95131d}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">28062526</property>
  <property name="kdenlive:file_hash">6563f52ff4e715fa79eaad6ea0705bea</property>
  <property name="kdenlive:record_start_frame">-1</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:meta.extractor.Bitrate:">2304 kb/s</property>
  <property name="kdenlive:meta.extractor.Copyright:">CC0 / WTFPL / Public domain</property>
  <property name="kdenlive:monitorPosition">0</property>
 </chain>
 <chain id="chain14" out="00:04:59.067">
  <property name="length">8973</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2489560/Downloads/AMBRurl_Campagne la nuit 4 (ID 1880)_LaSonotheque.fr.wav</property>
  <property name="mlt_service">avformat</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s32</property>
  <property name="meta.media.0.codec.sample_rate">48000</property>
  <property name="meta.media.0.codec.channels">2</property>
  <property name="meta.media.0.codec.layout">independent</property>
  <property name="meta.media.0.codec.name">pcm_s24le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 24-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">2304000</property>
  <property name="meta.attr.comment.markup">Campaign at night 4</property>
  <property name="meta.attr.encoded_by.markup">BigSoundBank.com</property>
  <property name="meta.attr.originator_reference.markup">1880</property>
  <property name="meta.attr.date.markup">2020-05-06</property>
  <property name="meta.attr.time_reference.markup">0</property>
  <property name="meta.attr.coding_history.markup">A=PCM,F=48000,W=24,M=stereo</property>
  <property name="meta.attr.copyright.markup">CC0 / WTFPL / Public domain</property>
  <property name="meta.attr.IKEY.markup">ambiance,campagne,exterieur,insecte,nature,nuit,atmosphere,soundscape,insect,chant,countryside,campaign,rural,nocturne,vent,wind,perche</property>
  <property name="meta.attr.IARL.markup">48.481879,0.964994</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">15</property>
  <property name="kdenlive:control_uuid">{f9510d91-34e7-46ee-8894-0eebd329b011}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">86142608</property>
  <property name="kdenlive:file_hash">cd76dee7108d820ffad229e01b6098ed</property>
  <property name="kdenlive:record_start_frame">-1</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:meta.extractor.Bitrate:">2304 kb/s</property>
  <property name="kdenlive:meta.extractor.Copyright:">CC0 / WTFPL / Public domain</property>
  <property name="kdenlive:monitorPosition">0</property>
 </chain>
 <chain id="chain15" out="00:00:42.733">
  <property name="length">1283</property>
  <property name="eof">pause</property>
  <property name="resource">C:/Users/2489560/Downloads/STORM_Pluie et orage (ID 0124)_LaSonotheque.fr.wav</property>
  <property name="mlt_service">avformat</property>
  <property name="meta.media.nb_streams">1</property>
  <property name="meta.media.0.stream.type">audio</property>
  <property name="meta.media.0.codec.sample_fmt">s16</property>
  <property name="meta.media.0.codec.sample_rate">44100</property>
  <property name="meta.media.0.codec.channels">2</property>
  <property name="meta.media.0.codec.layout">independent</property>
  <property name="meta.media.0.codec.name">pcm_s16le</property>
  <property name="meta.media.0.codec.long_name">PCM signed 16-bit little-endian</property>
  <property name="meta.media.0.codec.bit_rate">1411200</property>
  <property name="meta.attr.comment.markup">Rain and storm</property>
  <property name="meta.attr.encoded_by.markup">BigSoundBank.com</property>
  <property name="meta.attr.originator_reference.markup">0124</property>
  <property name="meta.attr.date.markup">2006-09-30</property>
  <property name="meta.attr.time_reference.markup">0</property>
  <property name="meta.attr.coding_history.markup">A=PCM,F=44100,W=16,M=stereo</property>
  <property name="meta.attr.copyright.markup">CC0 / WTFPL / Public domain</property>
  <property name="meta.attr.IKEY.markup">orage,pluie,eau,pleut,foudre,tonnerre,coup,averse,rain,thunderstorm,thunder,ambiance,clash,atmosphere,soundscape,raining,kick,nature,grondement,gronder,tonner,eclair,grosse,gros,fort,forte,thunderstruck</property>
  <property name="meta.attr.IARL.markup">48.576346,1.876454</property>
  <property name="seekable">1</property>
  <property name="audio_index">0</property>
  <property name="video_index">-1</property>
  <property name="astream">0</property>
  <property name="kdenlive:folderid">-1</property>
  <property name="kdenlive:id">16</property>
  <property name="kdenlive:control_uuid">{67424e50-2c37-4dc1-93e4-860bc06303f4}</property>
  <property name="kdenlive:clip_type">1</property>
  <property name="kdenlive:file_size">7546030</property>
  <property name="kdenlive:file_hash">006887a786320d29c739485dadbfc712</property>
  <property name="kdenlive:record_start_frame">-1</property>
  <property name="kdenlive:kextractor">1</property>
  <property name="kdenlive:meta.extractor.Bitrate:">1411 kb/s</property>
  <property name="kdenlive:meta.extractor.Copyright:">CC0 / WTFPL / Public domain</property>
 </chain>
 <playlist id="main_bin">
  <property name="kdenlive:folder.-1.2">Séquences</property>
  <property name="kdenlive:sequenceFolder">2</property>
  <property name="kdenlive:docproperties.audioChannels">2</property>
  <property name="kdenlive:docproperties.binsort">0</property>
  <property name="kdenlive:docproperties.browserurl">C:/Users/2489560/Documents/</property>
  <property name="kdenlive:docproperties.documentid">1794416751756</property>
  <property name="kdenlive:docproperties.enableTimelineZone">0</property>
  <property name="kdenlive:docproperties.enableexternalproxy">0</property>
  <property name="kdenlive:docproperties.enableproxy">0</property>
  <property name="kdenlive:docproperties.externalproxyparams"/>
  <property name="kdenlive:docproperties.generateimageproxy">0</property>
  <property name="kdenlive:docproperties.generateproxy">0</property>
  <property name="kdenlive:docproperties.guidesCategories">[
    {
        "color": "#9b59b6",
        "comment": "Catégorie 1",
        "index": 0
    },
    {
        "color": "#3daee9",
        "comment": "Catégorie 2",
        "index": 1
    },
    {
        "color": "#1abc9c",
        "comment": "Catégorie 3",
        "index": 2
    },
    {
        "color": "#1cdc9a",
        "comment": "Catégorie 4",
        "index": 3
    },
    {
        "color": "#c9ce3b",
        "comment": "Catégorie 5",
        "index": 4
    },
    {
        "color": "#fdbc4b",
        "comment": "Catégorie 6",
        "index": 5
    },
    {
        "color": "#f39c1f",
        "comment": "Catégorie 7",
        "index": 6
    },
    {
        "color": "#f47750",
        "comment": "Catégorie 8",
        "index": 7
    },
    {
        "color": "#da4453",
        "comment": "Catégorie 9",
        "index": 8
    }
]
</property>
  <property name="kdenlive:docproperties.kdenliveversion">26.08.3</property>
  <property name="kdenlive:docproperties.patchversion">1</property>
  <property name="kdenlive:docproperties.previewextension"/>
  <property name="kdenlive:docproperties.previewparameters"/>
  <property name="kdenlive:docproperties.profile">atsc_1080p_30</property>
  <property name="kdenlive:docproperties.proxyextension"/>
  <property name="kdenlive:docproperties.proxyimageminsize">2000</property>
  <property name="kdenlive:docproperties.proxyimagesize">800</property>
  <property name="kdenlive:docproperties.proxyminsize">1000</property>
  <property name="kdenlive:docproperties.proxyparams"/>
  <property name="kdenlive:docproperties.proxyresize">640</property>
  <property name="kdenlive:docproperties.seekOffset">30000</property>
  <property name="kdenlive:docproperties.sessionid">{cfc54d6d-5625-4c85-b0af-b1af693acdc2}</property>
  <property name="kdenlive:docproperties.uuid">{91e5eb31-9eec-4c68-a20b-793717e49a30}</property>
  <property name="kdenlive:docproperties.version">1.1</property>
  <property name="kdenlive:expandedFolders"/>
  <property name="kdenlive:binZoom">4</property>
  <property name="kdenlive:extraBins">project_bin:-1:0</property>
  <property name="kdenlive:documentnotes"/>
  <property name="kdenlive:documentnotesversion">2</property>
  <property name="kdenlive:docproperties.opensequences">{91e5eb31-9eec-4c68-a20b-793717e49a30}</property>
  <property name="kdenlive:docproperties.activetimeline">{91e5eb31-9eec-4c68-a20b-793717e49a30}</property>
  <property name="kdenlive:docproperties.layout">{
    "allDockWidgets": [
        {
            "lastCloseReason": 0,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 11,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": -1,
                "wasFloating": false
            },
            "uniqueName": "timeline"
        },
        {
            "lastCloseReason": 0,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 2,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 0,
                "wasFloating": false
            },
            "uniqueName": "project_bin"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 3,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 3,
                "wasFloating": false
            },
            "uniqueName": "library"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 12,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 2,
                "wasFloating": false
            },
            "uniqueName": "subtitles"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 4,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 2,
                "wasFloating": false
            },
            "uniqueName": "textedit"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 12,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 2,
                "wasFloating": false
            },
            "uniqueName": "timeremap"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 2,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 2,
                "wasFloating": false
            },
            "uniqueName": "markers"
        },
        {
            "lastCloseReason": 1,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 0,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 0,
                "wasFloating": false
            },
            "uniqueName": "screengrab"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 1,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 0,
                "wasFloating": false
            },
            "uniqueName": "audiospectrum"
        },
        {
            "lastCloseReason": 0,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 3,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 0,
                "wasFloating": false
            },
            "uniqueName": "clipmonitor"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 4,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 1,
                "wasFloating": false
            },
            "uniqueName": "projectmonitor"
        },
        {
            "lastCloseReason": 0,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 2,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 1,
                "wasFloating": false
            },
            "uniqueName": "clip_properties"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 4,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 4,
                "wasFloating": false
            },
            "uniqueName": "notes_widget"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 9,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 0,
                "wasFloating": false
            },
            "uniqueName": "media_browser"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 10,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 0,
                "wasFloating": false
            },
            "uniqueName": "onlineresources"
        },
        {
            "lastCloseReason": 0,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 12,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 1,
                "wasFloating": false
            },
            "uniqueName": "effect_stack"
        },
        {
            "lastCloseReason": 0,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 2,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": -1,
                "wasFloating": false
            },
            "uniqueName": "effect_list"
        },
        {
            "lastCloseReason": 0,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 2,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": -1,
                "wasFloating": false
            },
            "uniqueName": "transition_list"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 849,
                    "width": 905,
                    "x": 16,
                    "y": 82
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 2,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 2,
                "wasFloating": false
            },
            "uniqueName": "undo_history"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 12,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 2,
                "wasFloating": false
            },
            "uniqueName": "mixer"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 6,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 0,
                "wasFloating": false
            },
            "uniqueName": "vectorscope"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 5,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 0,
                "wasFloating": false
            },
            "uniqueName": "waveform"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 7,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 0,
                "wasFloating": false
            },
            "uniqueName": "rgb_parade"
        },
        {
            "lastCloseReason": 2,
            "lastPosition": {
                "lastFloatingGeometry": {
                    "height": 0,
                    "width": 0,
                    "x": 0,
                    "y": 0
                },
                "lastOverlayedGeometries": [],
                "placeholders": [
                    {
                        "isFloatingWindow": false,
                        "itemIndex": 8,
                        "mainWindowUniqueName": "KdenliveKDDock"
                    }
                ],
                "tabIndex": 0,
                "wasFloating": false
            },
            "uniqueName": "histogram"
        }
    ],
    "closedDockWidgets": [
        "library",
        "subtitles",
        "textedit",
        "timeremap",
        "markers",
        "screengrab",
        "audiospectrum",
        "clip_properties",
        "notes_widget",
        "media_browser",
        "onlineresources",
        "effect_list",
        "transition_list",
        "undo_history",
        "mixer",
        "vectorscope",
        "waveform",
        "rgb_parade",
        "histogram"
    ],
    "floatingWindows": [],
    "mainWindows": [
        {
            "affinities": null,
            "geometry": {
                "height": 2054,
                "width": 3840,
                "x": 0,
                "y": 34
            },
            "isVisible": true,
            "multiSplitterLayout": {
                "frames": {
                    "4625": {
                        "currentTabIndex": 0,
                        "dockWidgets": [
                            "projectmonitor",
                            "textedit",
                            "notes_widget"
                        ],
                        "geometry": {
                            "height": 890,
                            "width": 1352,
                            "x": 2484,
                            "y": 0
                        },
                        "id": "4625",
                        "isNull": false,
                        "mainWindowUniqueName": "KdenliveKDDock",
                        "objectName": "projectmonitor",
                        "options": 0
                    },
                    "4722": {
                        "currentTabIndex": 0,
                        "dockWidgets": [
                            "project_bin",
                            "transition_list",
                            "effect_list",
                            "clip_properties",
                            "undo_history"
                        ],
                        "geometry": {
                            "height": 890,
                            "width": 1176,
                            "x": 0,
                            "y": 0
                        },
                        "id": "4722",
                        "isNull": false,
                        "mainWindowUniqueName": "KdenliveKDDock",
                        "objectName": "project_bin",
                        "options": 0
                    },
                    "4901": {
                        "currentTabIndex": 1,
                        "dockWidgets": [
                            "mixer",
                            "effect_stack",
                            "timeremap",
                            "subtitles"
                        ],
                        "geometry": {
                            "height": 1031,
                            "width": 782,
                            "x": 3054,
                            "y": 890
                        },
                        "id": "4901",
                        "isNull": false,
                        "mainWindowUniqueName": "KdenliveKDDock",
                        "objectName": "effect_stack",
                        "options": 0
                    },
                    "5037": {
                        "currentTabIndex": 0,
                        "dockWidgets": [
                            "clipmonitor",
                            "library"
                        ],
                        "geometry": {
                            "height": 890,
                            "width": 1308,
                            "x": 1176,
                            "y": 0
                        },
                        "id": "5037",
                        "isNull": false,
                        "mainWindowUniqueName": "KdenliveKDDock",
                        "objectName": "clipmonitor",
                        "options": 0
                    },
                    "5099": {
                        "currentTabIndex": 0,
                        "dockWidgets": [
                            "timeline"
                        ],
                        "geometry": {
                            "height": 1031,
                            "width": 3054,
                            "x": 0,
                            "y": 890
                        },
                        "id": "5099",
                        "isNull": false,
                        "mainWindowUniqueName": "KdenliveKDDock",
                        "objectName": "timeline",
                        "options": 0
                    }
                },
                "layout": {
                    "children": [
                        {
                            "children": [
                                {
                                    "children": [
                                        {
                                            "isContainer": false,
                                            "isVisible": false,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 440,
                                                    "width": 95,
                                                    "x": 0,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524287,
                                                    "width": 524279
                                                },
                                                "minSize": {
                                                    "height": 90,
                                                    "width": 80
                                                },
                                                "percentageWithinParent": 0.0
                                            }
                                        },
                                        {
                                            "isContainer": false,
                                            "isVisible": false,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 440,
                                                    "width": 103,
                                                    "x": 0,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524265,
                                                    "width": 524270
                                                },
                                                "minSize": {
                                                    "height": 90,
                                                    "width": 80
                                                },
                                                "percentageWithinParent": 0.0
                                            }
                                        },
                                        {
                                            "guestId": "4722",
                                            "isContainer": false,
                                            "isVisible": true,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 890,
                                                    "width": 1176,
                                                    "x": 0,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524325,
                                                    "width": 524293
                                                },
                                                "minSize": {
                                                    "height": 295,
                                                    "width": 298
                                                },
                                                "percentageWithinParent": 0.306687565308255
                                            }
                                        },
                                        {
                                            "guestId": "5037",
                                            "isContainer": false,
                                            "isVisible": true,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 890,
                                                    "width": 1308,
                                                    "x": 1176,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524325,
                                                    "width": 524293
                                                },
                                                "minSize": {
                                                    "height": 238,
                                                    "width": 326
                                                },
                                                "percentageWithinParent": 0.34117032392894464
                                            }
                                        },
                                        {
                                            "guestId": "4625",
                                            "isContainer": false,
                                            "isVisible": true,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 890,
                                                    "width": 1352,
                                                    "x": 2484,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524325,
                                                    "width": 524293
                                                },
                                                "minSize": {
                                                    "height": 487,
                                                    "width": 674
                                                },
                                                "percentageWithinParent": 0.35214211076280044
                                            }
                                        },
                                        {
                                            "isContainer": false,
                                            "isVisible": false,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 440,
                                                    "width": 82,
                                                    "x": 1832,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524287,
                                                    "width": 524287
                                                },
                                                "minSize": {
                                                    "height": 90,
                                                    "width": 80
                                                },
                                                "percentageWithinParent": 0.0
                                            }
                                        },
                                        {
                                            "isContainer": false,
                                            "isVisible": false,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 440,
                                                    "width": 167,
                                                    "x": 1747,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524287,
                                                    "width": 524251
                                                },
                                                "minSize": {
                                                    "height": 90,
                                                    "width": 80
                                                },
                                                "percentageWithinParent": 0.0
                                            }
                                        },
                                        {
                                            "isContainer": false,
                                            "isVisible": false,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 440,
                                                    "width": 92,
                                                    "x": 1822,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524287,
                                                    "width": 524287
                                                },
                                                "minSize": {
                                                    "height": 90,
                                                    "width": 80
                                                },
                                                "percentageWithinParent": 0.0
                                            }
                                        },
                                        {
                                            "isContainer": false,
                                            "isVisible": false,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 440,
                                                    "width": 81,
                                                    "x": 1833,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524287,
                                                    "width": 524287
                                                },
                                                "minSize": {
                                                    "height": 90,
                                                    "width": 80
                                                },
                                                "percentageWithinParent": 0.0
                                            }
                                        },
                                        {
                                            "isContainer": false,
                                            "isVisible": false,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 508,
                                                    "width": 478,
                                                    "x": 1074,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 523905,
                                                    "width": 523960
                                                },
                                                "minSize": {
                                                    "height": 90,
                                                    "width": 80
                                                },
                                                "percentageWithinParent": 0.0
                                            }
                                        },
                                        {
                                            "isContainer": false,
                                            "isVisible": false,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 508,
                                                    "width": 378,
                                                    "x": 1536,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524174,
                                                    "width": 524011
                                                },
                                                "minSize": {
                                                    "height": 90,
                                                    "width": 80
                                                },
                                                "percentageWithinParent": 0.0
                                            }
                                        }
                                    ],
                                    "isContainer": true,
                                    "isVisible": false,
                                    "orientation": 1,
                                    "sizingInfo": {
                                        "geometry": {
                                            "height": 890,
                                            "width": 3836,
                                            "x": 0,
                                            "y": 0
                                        },
                                        "maxSizeHint": {
                                            "height": 524325,
                                            "width": 1572879
                                        },
                                        "minSize": {
                                            "height": 487,
                                            "width": 1298
                                        },
                                        "percentageWithinParent": 0.4636572302983933
                                    }
                                },
                                {
                                    "children": [
                                        {
                                            "guestId": "5099",
                                            "isContainer": false,
                                            "isVisible": true,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 1031,
                                                    "width": 3054,
                                                    "x": 0,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524338,
                                                    "width": 524300
                                                },
                                                "minSize": {
                                                    "height": 144,
                                                    "width": 95
                                                },
                                                "percentageWithinParent": 0.7961658841940532
                                            }
                                        },
                                        {
                                            "guestId": "4901",
                                            "isContainer": false,
                                            "isVisible": true,
                                            "sizingInfo": {
                                                "geometry": {
                                                    "height": 1031,
                                                    "width": 782,
                                                    "x": 3054,
                                                    "y": 0
                                                },
                                                "maxSizeHint": {
                                                    "height": 524325,
                                                    "width": 524293
                                                },
                                                "minSize": {
                                                    "height": 269,
                                                    "width": 336
                                                },
                                                "percentageWithinParent": 0.2038341158059468
                                            }
                                        }
                                    ],
                                    "isContainer": true,
                                    "isVisible": false,
                                    "orientation": 1,
                                    "sizingInfo": {
                                        "geometry": {
                                            "height": 1031,
                                            "width": 3836,
                                            "x": 0,
                                            "y": 890
                                        },
                                        "maxSizeHint": {
                                            "height": 524325,
                                            "width": 1048593
                                        },
                                        "minSize": {
                                            "height": 269,
                                            "width": 431
                                        },
                                        "percentageWithinParent": 0.5363427697016068
                                    }
                                }
                            ],
                            "isContainer": true,
                            "isVisible": false,
                            "orientation": 2,
                            "sizingInfo": {
                                "geometry": {
                                    "height": 1921,
                                    "width": 3836,
                                    "x": 0,
                                    "y": 0
                                },
                                "maxSizeHint": {
                                    "height": 1048650,
                                    "width": 1048593
                                },
                                "minSize": {
                                    "height": 756,
                                    "width": 1298
                                },
                                "percentageWithinParent": 1.0
                            }
                        }
                    ],
                    "isContainer": true,
                    "isVisible": false,
                    "orientation": 1,
                    "sizingInfo": {
                        "geometry": {
                            "height": 1921,
                            "width": 3836,
                            "x": 0,
                            "y": 0
                        },
                        "maxSizeHint": {
                            "height": 16777215,
                            "width": 16777215
                        },
                        "minSize": {
                            "height": 90,
                            "width": 80
                        },
                        "percentageWithinParent": 0.0
                    }
                }
            },
            "normalGeometry": {
                "height": 0,
                "width": 0,
                "x": 0,
                "y": 0
            },
            "options": 0,
            "screenIndex": 0,
            "screenSize": {
                "height": 2160,
                "width": 3840
            },
            "uniqueName": "KdenliveKDDock",
            "windowState": 2
        }
    ],
    "screenInfo": [
        {
            "devicePixelRatio": 1.0,
            "geometry": {
                "height": 2160,
                "width": 3840,
                "x": 0,
                "y": 0
            },
            "index": 0,
            "name": "CB322QK"
        }
    ],
    "serializationVersion": 3
}</property>
  <property name="xml_retain">1</property>
  <entry in="00:00:00.000" out="00:00:00.000" producer="{91e5eb31-9eec-4c68-a20b-793717e49a30}"/>
  <entry in="00:00:00.000" out="00:00:04.967" producer="producer1"/>
  <entry in="00:00:00.000" out="00:01:29.400" producer="chain8"/>
  <entry in="00:00:00.000" out="00:00:03.067" producer="chain9"/>
  <entry in="00:00:00.000" out="00:03:00.067" producer="chain10"/>
  <entry in="00:00:00.000" out="00:04:05.200" producer="chain11"/>
  <entry in="00:00:00.000" out="00:00:09.033" producer="chain12"/>
  <entry in="00:00:00.000" out="00:01:37.400" producer="chain13"/>
  <entry in="00:00:00.000" out="00:04:59.067" producer="chain14"/>
  <entry in="00:00:00.000" out="00:00:42.733" producer="chain15"/>
 </playlist>
 <tractor id="tractor10" in="00:00:00.000" out="00:01:05.000">
  <property name="kdenlive:projectTractor">1</property>
  <track in="00:00:00.000" out="00:01:05.000" producer="{91e5eb31-9eec-4c68-a20b-793717e49a30}"/>
 </tractor>
</mlt>
ng evs3.kdenlive…]()


Pour mon EVS3, j'ai commencer par trouver une image qui me convenais et avec laquelle j'allais illustré ma petite mise en scène sonore. Ensuite j'ai essayer des sons pour former ma vidéo. J'ai tout d'abord commencer par allé sur une application de sons libre de doit et j'ai commencer à en écouter une tonne de sons, afin de sélectionné ceux qui me convenais pour mon projet. J'ai ensuite jouer avec les longueurs de mes sons pour les superposés un par un sur mon image initiale. Pour certain sons je les ai dupliqué ou déplacer ou bien couper. Je me suis ensuite penché vers le résultat final et je me suis demander si j'étais satisfaite de mon projet. J'ai répondu que oui! Je suis satisfaite du résultat de mes différent sons que j'ai sélectionné et une fois ensemble je trouve le résultat très intéressant. Il est illustré dans mo projet une montagne enneiger avec des bruit d'oiseaux et de vent principalement. Il y a aussi le bruit de petit animaux et un passage de moutons rapide. 

<img width="3839" height="2159" alt="Capture d’écran 2026-11-11 131831" src="https://github.com/user-attachments/assets/79c5dacc-3911-4ce9-aa2c-ff1ae1906efc" />

Liens des sons: 
(Tout les sons provienne du même site libre de droit)
https://lasonotheque.org/pluie-et-orage-s0124.html

- [WINDDsgn_Vent (ID 0595)_LaSonotheque.fr (1).wav](https://github.com/user-attachments/files/34699377/WINDDsgn_Vent.ID.0595._LaSonotheque.fr.1.wav)
- [BIRDSong_Rouge gorge 4 (ID 1670)_LaSonotheque.fr.wav](https://github.com/user-attachments/files/34699383/BIRDSong_Rouge.gorge.4.ID.1670._LaSonotheque.fr.wav)
- [MUSCInst_Bol tibetain frappe 3 (ID 2554)_LaSonotheque.fr.wav](https://github.com/user-attachments/files/34699717/MUSCInst_Bol.tibetain.frappe.3.ID.2554._LaSonotheque.fr.wav)
- [STORM_Pluie et orage (ID 0124)_LaSonotheque.fr.wav](https://github.com/user-attachments/files/34700170/STORM_Pluie.et.orage.ID.0124._LaSonotheque.fr.wav)

*  4 autres sons sont inclus mais le lien de sons est trop long pour les déposés ici! *
  - Les oiseaux qui chantes
  - Les arbustes qui craques
  - Le troupeaux de moutons
  - Le bruit des grillions 
