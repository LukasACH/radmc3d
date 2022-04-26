add_executable(radmc3d
    main.f90
    amr_module.f90
    constants_module.f90
    rtglobal_module.f90
    dust_module.f90
    polarization_module.f90
    mathroutines_module.f90
    lines_module.f90
    ioput_module.f90
    amrray_module.f90
    stars_module.f90
    camera_module.f90
    gascontinuum_module.f90
    montecarlo_module.f90
    quantum_module.f90
    userdef_module.f90
    namelist_module.f90
    sources_module.f90
)

add_compile_options(-O2 -fopenmp)