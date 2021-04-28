# C# Binding for UEFI

## How to use

- Follow instructions in [ZeroSharp](https://github.com/MichalStrehovsky/zerosharp/tree/master/efi-no-runtime). **NOTE : The csproj method doesn't suit latest version of corert.**

- COPY *.cs in this project to your project, remove all the EFI stuff from the example, and modity your build script or project file in need.

- Run!

## Haders INCLUDED

- eficon.h -> EFICon.cs
- efiapi.h -> EFIAPI.cs
- efitypes.h, efierr.h -> EFITypes.cs
- efidevp.h -> EFIDevices.cs (patrial)