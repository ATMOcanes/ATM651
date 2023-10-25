# Quite good (test-ready) outputs from https://claude.ai/chat/
# Problematic ones are [here](https://github.com/ATMOcanes/ATM651/blob/master/Glossary_table_Problematic_Ones.md)
## Biggest remaining problem: vectors treated as one dimension (like advection line 11)
## You should know how to do better (vector form) 
### Textbook, or compare to GPT-4 [here](https://docs.google.com/document/d/1ffX5VAzhdYgoUo_GcoPSI_Ulf-uJzziXfkGAAREHuJE/edit)

Word | Verbal Definition | Mathematical Definition/Formula | Units
|-|-|-|-|  
function | A mathematical relationship where each input has a single output | f(x) | N/A
coordinate | A number that defines a position along an axis | x, y, z | m, km
argument | Independent variable of a function | x in f(x) | N/A  
slope | Rate of change of a variable | dy/dx; often **dz/dx** | m/m, km/km; **m/(100km)** 
curvature | Rate of change of slope | d^2y/dx^2 | 1/m
del, nabla | Vector differential operator | ∇ | 1/m
curl | Rotation of a vector field | (∇ x F) | 1/s  
divergence | Outward flux of a vector field | ∇ · F | 1/s
gradient | Rate of change of a scalar field | ∇φ | m/m, km/km
Laplacian | Divergence of gradient, measures concavity | ∇^2φ | 1/m^2
kinematics | Description of motion | N/A | N/A
advection | Transport by fluid motion | -u ∂φ/∂x | units of φ/s
diffusion | Spreading of quantity by random motion | ∂φ/∂t = K ∇^2φ | units of φ/s
meridional | North-south direction | N/A | N/A
zonal | West-east direction | N/A | N/A
streamlines | Curve tangent to velocity | N/A | N/A
trajectories | Path of air parcel | N/A | N/A
isotachs | Lines of equal wind speed | N/A | N/A
deformation | Change in shape | ∂u/∂x - ∂v/∂y | 1/s
vorticity | Rotation or spin | (∇ x u) · k | 1/s
divergence | Outward flux | ∇ · u | 1/s
shear | Change in velocity across space | ∂u/∂y | 1/s
tracer | Passive scalar transported by flow | N/A | N/A
up-gradient | Toward higher values | N/A | N/A
down-gradient | Toward lower values | N/A | N/A
Coriolis force | Apparent force due to Earth's rotation | Fc = -2mΩ x u | N 
geopotential | Gravitational potential energy per unit mass | φ = gz | m^2/s^2
hydrostatic | Vertical balance between pressure gradient and gravity | ∂p/∂z = -ρg | Pa/m
isobars | Lines of constant pressure | N/A | N/A
boundary layer | Layer where friction important | N/A | N/A
static stability | Resistance to vertical motion | N^2 = (g/θ)(dθ/dz) | 1/s^2
geostrophic | Balance between Coriolis and pressure gradient | fcug = -1/ρ ∂p/∂x | N/A
extratropical | Outside the tropics | N/A | N/A  
thermal wind balance | Vertical wind shear proportional to horizontal temperature gradient | f ∂ug/∂z = -(g/θ)∂θ/∂y | m/s/m
sub-geostrophic | Wind slower than geostrophic | | N/A
constructive interference | Amplification of waves in phase | N/A | N/A
destructive interference | Cancellation of out-of-phase waves | N/A | N/A
jet stream | Narrow band of strong winds | N/A | m/s
gradient wind | Velocity in cyclostrophic balance | | m/s
thermal wind | Vertical shear proportional to temperature gradient | | m/s
hydrostatic | Vertical balance between pressure gradient and gravity | N/A | N/A
planetary vorticity | Earth's spin | f = 2Ωsin(φ) | 1/s
absolute vorticity | Planetary + relative vorticity | ζ = ζr + f | 1/s
relative vorticity | Spin of air relative to Earth | ζr = ∇ x u | 1/s
warming rate | Rate of temperature increase | ∂T/∂t | K/s 
initial condition | Model state at start of forecast | N/A | N/A
boundary condition | Condition on model domain edges | N/A | N/A
forecast | Predicted future state | N/A | N/A
hindcast | Retrospective forecast | N/A | N/A
nowcast | Very short term forecast | N/A | N/A
inflection point | Point where curvature changes sign | d^2y/dx^2 = 0 | N/A
ridge | Elongated maximum | N/A | N/A
trough | Elongated minimum | N/A | N/A  
anomaly | Difference from time mean | φ' = φ - <φ> | units of φ
oscillation | Fluctuation in time | N/A | N/A
sinusoidal | Shape of sine wave | sin(kx-ωt) | N/A
wavelength | Spatial scale of periodic wave | λ | m, km
amplitude | Maximum disturbance from equilibrium | A | units of φ
phase | Position within cycle of oscillation | φ = kx - ωt | rad
frequency | Number of cycles per time | ν = 1/T | 1/s  
wavenumber | Spatial frequency of wave | k = 2π/λ | 1/m
evolution | Development in time | N/A | N/A
steering flow | Larger-scale flow advecting smaller-scale eddy | N/A | m/s
stationary wave | Wave with zero phase speed | N/A | N/A
steady state | Time-independent solution | ∂φ/∂t = 0 | N/A
planetary wave | Global scale wave in atmosphere | N/A | N/A
Rossby wave | Large scale atmospheric wave due to vorticity advection | N/A | N/A
synoptic scale | 1000s of km, high/low pressure systems | N/A | N/A
convective scale | Individual thunderstorms | N/A | N/A 
mesoscale | 10s to 100s of km | N/A | N/A
mean | Average value | <φ> = (1/N)Σφ | units of φ
standard deviation | Spread around mean | σ = sqrt(<φ^2> - <φ>^2) | units of φ
reconstruction | Approximating field from limited data | N/A | N/A
decomposition | Separating into components | N/A | N/A  
prognostic equation | Predicts future value | ∂φ/∂t = F | units of φ/s  
diagnostic equation | Calculates from other variables | φ = f(u,v,T,etc.) | units of φ
potential temperature | Temp measure of internal energy | θ = T(p0/p)^κ | K
isentropic | Constant potential temperature surface | N/A | N/A
isentropes | Contours of potential temperature | N/A | N/A
thermodynamic energy equation | Atmospheric internal energy budget | Cp(DT/Dt) = ... | W/m^3
diabatic | Processes changing thermal energy | N/A | N/A  
adiabatic | Processes conserving thermal energy | N/A | N/A
flux convergence | Net inward flux | -∇·F | 
longwave radiation | Terrestrial radiation | N/A | W/m^2
absorption | Radiation energy converted to heat | N/A | N/A
emission | Radiation energy emitted | N/A | W/m^2 
latent heat release | Energy change in phase transition | L dq | J/kg
mixed layer | Well-mixed atmospheric boundary layer | N/A | m
lapse rate | Rate of temperature decrease with height | Γ = -dT/dz | K/km
subsidence | Downward vertical motion | w < 0 | m/s  
ascent | Upward vertical motion | w > 0 | m/s
frontal zone | Boundary between air masses | N/A | N/A
convection | Vertical circulation due to instability | N/A | N/A
ITCZ | Zone of tropical rainfall near equator | N/A | N/A
mass continuity equation | Mass conservation constraint | Dρ/Dt + ρ∇·u = 0 | kg/m^3s
internal wave | Gravity wave propagating within fluid | N/A | N/A
numerical model | Mathematical model solved numerically | N/A | N/A
baroclinic instability | Instability from horizontal temp gradient | N/A | N/A
tropics | Zone from tropics to ~30 deg latitude | N/A | N/A
subtropics | ~20-35 deg latitude | N/A | N/A  
midlatitudes | ~35-60 deg latitude | N/A | N/A
extratropics | Outside tropics, poleward of ~30 deg | N/A | N/A
subpolar | ~60-75 deg latitude | N/A | N/A
polar | 75-90 deg latitude | N/A | N/A
trade winds | Tropical easterlies near surface | N/A | m/s
Hadley cell | Tropical overturning circulation | N/A | N/A
monsoon | Seasonally reversing tropical circulation | N/A | N/A
tropical cyclone | Organized tropical storm | N/A | N/A
heat engine | System converting thermal to mechanical energy | N/A | N/A
numerical weather prediction | Computer forecasting from models | N/A | N/A  
data assimilation | Incorporating observations into model | N/A | N/A
deterministic predictability | Potential skill from model physics | N/A | N/A
butterfly effect | Sensitivity to small changes in initial conditions | N/A | N/A
attractor | State toward which system evolves | N/A | N/A
ensemble mean | Average of ensemble member forecasts | N/A | N/A
ensemble spread | Variability among ensemble members | N/A | N/A
sector | Limited geographic region | N/A | N/A  
hemisphere | Half the globe | N/A | N/A
skill | Forecast quality relative to standard | N/A | N/A
streamfunction | Velocity potential for nondivergent flow | ψ | m^2/s
irrotational | Zero curl/vorticity | ∇ x u = 0 | N/A
velocity potential | Scalar potential for irrotational flow | φ | m^2/s
nondivergent | Zero divergence | ∇ · u = 0 | N/A
buoyancy | Upward force from density variation | B = -g ρ'/ρ | m/s^2
instability | Tendency to amplify disturbances | N/A | N/A
stable | Resistant to disturbance growth | N/A | N/A  
saturation vapor pressure | Max vapor pressure over liquid/ice es(T) | N/A | Pa
dry static energy | CpT + gz | J/kg
moist static energy | CpT + gz + Lq | J/kg
Sverdrup balance | Wind stress curl balance by vertical motion | βv = curl(τ/ρH) | m^2/s
crystallization | Phase transition from liquid to solid | N/A | N/A
sublimation | Phase transition from solid to gas | N/A | N/A
condensation | Phase transition from gas to liquid | N/A | N/A
precipitation | Fall of liquid or solid water | N/A | mm
evaporation | Phase transition from liquid to gas | N/A | mm/day
