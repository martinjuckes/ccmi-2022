# Conformance Notes

Notes on issues around conformance to the requirements of the CCMI data request.

## CF Conventions for atmosphere_hybrid_sigma_pressure_coordinate

There was an error (inherited from CMIP6) in the initial version of the CMOR tables resulting in the use of `standard_name=air_pressure` where `surface_air_pressure` should have been used. 
The tables were corrected in May 2021, but data produced using the earlier tables will be accepted. See https://github.com/cedadev/ccmi-2022/issues/10

## Tracking ID

There was initially uncertainty about how to use this attribute. Initial versions of the table include a `hdl:....` prefix, but the implied handle.net service will not be implemented. 
The tables were later modified to exclude the prefix. Either version will be accepted. https://github.com/cedadev/ccmi-2022/issues/9
