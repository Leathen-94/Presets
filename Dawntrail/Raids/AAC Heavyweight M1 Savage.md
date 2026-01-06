 # WORK IN PROGRESS - Currently up to blade intermission phase (Last updated 6th Jan 13:53)

NOTE:

You should have `ToolerOfLight` latest presets for this fight [Here]([https://github.com/ToolerofLight/myfiles/blob/main/README.md](https://github.com/ToolerofLight/myfiles/blob/main/Splatoon/%5B7.x%5D%E9%BB%84%E9%87%91%E3%81%AE%E3%83%AC%E3%82%AC%E3%82%B7%E3%83%BC/%E9%9B%B6%E5%BC%8F/%5B7.4%5D%E3%82%A2%E3%83%AB%E3%82%AB%E3%83%87%E3%82%A3%E3%82%A2%E3%83%98%E3%83%93%E3%83%BC%E7%B4%9A1%E5%B1%A4%E9%9B%B6%E5%BC%8F%20.md))
The code below are addiitional elements, that I am finding usefull, or for later mechanics not included above
As Tooler expands their set, I will be disabling any duplicates below


Additions
- Vamp Stomp Debuff - Proximity circle so you can keep awway from others
- Aetherletting - cone telegraph
- Aetherletting - circle mark where yours will drop
- Half Moon - half room cleve, im sure there are other ID's to capture

  
```
~Lv2~{"Name":"Spinning Blades Phases","Group":"AAC Heavyweight M4 Savage","ZoneLockH":[1321],"ElementsL":[{"Name":"Horizontal Blade - Warning","type":3,"refY":10.0,"radius":2.0,"color":4278236159,"fillIntensity":0.3,"thicc":0.0,"refActorNPCNameID":14499,"refActorComparisonType":6,"includeHitbox":true,"includeRotation":true,"onlyVisible":true,"FillStep":2.0},{"Name":"Horizontal Blade - Circle","type":1,"radius":2.0,"fillIntensity":0.3,"refActorNPCNameID":14499,"refActorComparisonType":6,"includeHitbox":true,"includeRotation":true,"onlyVisible":true},{"Name":"Horizontal Blade - Arrow","type":3,"refY":4.0,"radius":0.0,"fillIntensity":0.345,"thicc":5.0,"refActorNPCNameID":14499,"refActorComparisonType":6,"includeRotation":true,"onlyVisible":true,"LineEndA":1},{"Name":"Vertical Blade - Warning","type":3,"refY":10.0,"radius":0.0,"color":4278236159,"fillIntensity":0.3,"thicc":0.0,"refActorNPCNameID":14500,"refActorComparisonType":6,"includeHitbox":true,"includeRotation":true,"onlyVisible":true,"FillStep":2.0},{"Name":"Vertical Blade - Circle","type":1,"radius":0.0,"fillIntensity":0.3,"refActorNPCNameID":14500,"refActorComparisonType":6,"includeHitbox":true,"includeRotation":true,"onlyVisible":true},{"Name":"Vertical Blade - Arrow","type":3,"refY":4.0,"radius":0.0,"fillIntensity":0.345,"thicc":5.0,"refActorNPCNameID":14500,"refActorComparisonType":6,"includeRotation":true,"onlyVisible":true,"LineEndA":1}]}
~Lv2~{"Name":"Half Moon","Group":"AAC Heavyweight M4 Savage","ZoneLockH":[1321],"ElementsL":[{"Name":"Left First (Left)","type":4,"refY":46.58,"offX":4.0,"radius":40.0,"coneAngleMin":-90,"coneAngleMax":90,"fillIntensity":0.3,"refActorNPCNameID":14300,"refActorRequireCast":true,"refActorCastId":[45946],"refActorUseCastTime":true,"refActorCastTimeMax":4.5,"refActorComparisonType":6,"includeRotation":true,"AdditionalRotation":4.712389,"FillStep":2.0},{"Name":"Left First (Right)","type":4,"refY":46.58,"offX":-4.0,"radius":40.0,"coneAngleMin":-90,"coneAngleMax":90,"fillIntensity":0.3,"refActorNPCNameID":14300,"refActorRequireCast":true,"refActorCastId":[45946],"refActorUseCastTime":true,"refActorCastTimeMin":4.5,"refActorCastTimeMax":8.0,"refActorUseOvercast":true,"refActorComparisonType":6,"includeRotation":true,"AdditionalRotation":1.5707964,"FillStep":2.0}]}
~Lv2~{"Name":"Vamp Stop Debuff","Group":"AAC Heavyweight M4 Savage","ZoneLockH":[1321],"MaxDistance":10.0,"UseDistanceLimit":true,"DistanceLimitType":1,"ElementsL":[{"Name":"Curse of the Bombpyre","type":1,"radius":7.0,"Filled":false,"fillIntensity":0.5,"refActorPlaceholder":["<2>","<3>","<4>","<5>","<6>","<7>","<8>","<1>"],"refActorRequireBuff":true,"refActorBuffId":[4729],"refActorComparisonType":5,"DistanceSourceX":95.367294,"DistanceSourceY":108.081665}]}
~Lv2~{"Name":"Aetherletting","Group":"AAC Heavyweight M4 Savage","ZoneLockH":[1321],"ElementsL":[{"Name":"Cone","type":4,"radius":22.0,"coneAngleMin":-22,"coneAngleMax":22,"fillIntensity":0.5,"castAnimation":3,"animationColor":4294903296,"refActorNPCNameID":14300,"refActorRequireCast":true,"refActorCastId":[45969],"refActorUseCastTime":true,"refActorCastTimeMin":6.0,"refActorCastTimeMax":8.7,"refActorComparisonType":6,"includeRotation":true,"RenderEngineKind":1},{"Name":"Mark","type":1,"radius":5.0,"fillIntensity":0.3,"refActorComparisonType":7,"refActorVFXPath":"vfx/lockon/eff/lockon5_line_1p.avfx","refActorVFXMax":5000}]}
```
