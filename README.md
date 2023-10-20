# qu-mica-gases-5
1
# 1. El huracán Sandy (“supertormenta Sandy”) fue uno de los más destructivos en
# los últimos años y afectó el Caribe, Cuba, las Bahamas y 24 estados de la
# costa este de Estados Unidos. La presión más baja registrada en este huracán
# fue de 705 mmHg. ¿Cuál fue la presión en kPa?
# Dato: 1 atm = 1.01325x10E5 Pa = 760 mmHg
presion_mmHg = 705 # mmHg
presion_kPa = presion_mmHg*((1.01325*100)/760) print("la presión en kPa es: ", round(presion_kPa,2))


2
presiones = [0.9579 ,0.96843 ,0.928 ,1.105 ]
sorted(presiones)
print(sorted(presiones))
¿En dónde sería más fácil beber agua con un popote, en la cima o al pie del monte Everest?
Sería más fácil beber agua con un popote al pie del monte Everest debido a la mayor presión atmosférica en comparación con la cima, donde la presión es muy baja


3
# Definir las temperaturas iniciales y finales
T1_a = 200  # en Kelvin
T2_a = 400  # en Kelvin
T1_b = 200 + 273.15
T2_b = 400 + 273.15
# Calcular los cambios de volumen
V1_V2_a = T2_a / T1_a
V1_V2_b = T2_b / T1_b
# Comparar los cambios de volumen
if V1_V2_a > V1_V2_b:
print("El cambio de volumen es mayor en el escenario (a) de 200 K a 400 K.")
else:
print("El cambio de volumen es mayor en el escenario (b) de 200 ºC a 400 ºC.")


4
n = 1.82  # Moles
V = 5.43  # Litros
T = 69.5 + 273.15  # Temperatura en Kelvin (convertir de Celsius) R = 0.082057  # L·atm/(K·mol)
# Calcular la presión P = (n * R * T) / V
# Imprimir el resultado print(P)



5
R = 0.0821  # L·atm/(K·mol)
P = 6.54   # Presión en atmósferas
T = 76 + 273.15   # Temperatura en Kelvin (convertir de Celsius) n = 2.12   # Moles
# Calcular el volumen usando la ecuación de estado de los gases ideales
V = (n * R * T) / P
# Convertir el volumen a litros
V_litros = V * 1000  # 1 litro = 1000 cm^3 print(V)


6
masa_NH3 = 7.40  # en gramos
masa_molar_NH3 = 17.04 # g/mol (masa molar del NH3) V_molar = 22.41 # Litros/mol (volumen molar a TPE)
# Convertir la masa a moles
moles_NH3 = masa_NH3 / masa_molar_NH3
# Calcular el volumen ocupado
V_litros = moles_NH3 * V_molar print(V_litros)


7
V_molar_TPE = 22.4  # Volumen molar a TPE en L/mol
# Calcular volúmenes
# a) 0.82 moles de He
moles_He = 0.82
V_He = moles_He * V_molar_TPE
# b) 24 g de N2
masa_N2 = 24 # en gramos
masa_molar_N2 = 28  # g/mol (masa molar del N2)
moles_N2 = masa_N2 / masa_molar_N2
V_N2 = moles_N2 * V_molar_TPE
# c) 5.0 x 10^3 moléculas de Cl2
moles_Cl2 = 5.0e3 / 6.022e23  # Convertir moléculas a moles V_Cl2 = moles_Cl2 * V_molar_TPE
# Calcular densidades
# Densidad = Masa molar / Volumen molar
# Densidad se expresa en g/L
# Densidad de He
densidad_He = 4 / V_molar_TPE
# Densidad de N2
densidad_N2 = 28 / V_molar_TPE
# Densidad de Cl2
densidad_Cl2 = 71 / V_molar_TPE
# Mostrar resultados
(V_He, V_N2, V_Cl2), (densidad_He, densidad_N2, densidad_Cl2)
Volumenes = (V_He , V_N2 , V_Cl2) sorted(Volumenes) print(sorted(Volumenes))
print(V_He > V_N2 and V_He > V_Cl2) print(V_N2 > V_He and V_N2 > V_Cl2)


8
# Definir las constantes
P1 = 1.0  # Presión inicial en atm V1 = 0.55  # Volumen inicial en L P2 = 0.40  # Presión final en atm# Calcular el volumen final V1xP1 = V2P2
V2 = (P1 * V1) / P2
# Mostrar el resultado
print(V2)



9
# Definir las constantes
P1 = 726 # Presión inicial en mmHg V1 = 946 # Volumen inicial en mL
V2 = 154 # Volumen final en mL
# Calcular la presión final
P2 = (P1 * V1) / V2 print(P2)



10
# Definir las constantes
P1 = 1.20 # Presión inicial en atm
T1_Celsius = 18 # Temperatura inicial en Celsius
T2_Celsius = 85 # Temperatura final en Celsius
# Convertir temperaturas a Kelvin
T1 = T1_Celsius + 273 # Temperatura inicial en Kelvin T2 = T2_Celsius + 273  # Temperatura final en Kelvin
# Calcular la presión final
P2 = P1 * (T2 / T1)
# Mostrar el resultado
print(P2)




11
# Definir las constantes
P1 = 6.4 # Presión inicial en atm
V1 = 2.1 # Volumen inicial en mL
T1_Celsius = 8  # Temperatura inicial en Celsius
P2 = 1.0 # Presión final en atm
T2_Celsius = 25 # Temperatura final en Celsius
# Convertir temperaturas a Kelvin
T1 = T1_Celsius + 273  # Temperatura inicial en Kelvin T2 = T2_Celsius + 273  # Temperatura final en Kelvin # Calcular el volumen final (V2)V2 = (P1 * V1 * T2) / (P2 * T1)
# Mostrar el resultado
print(V2)



12
# Definir los datos dados
P1 = 1.2 # atm
V1 = 4.0 # L
T1 = 66 + 273.15  # ºC a K
V2 = 1.7 # L
T2 = 42 + 273.15  # ºC a K
# Aplicar la Ley de Boyle-Mariotte para encontrar P2
P2 = (P1 * V1) / V2
print(P2)




13
# Datos dados
P = 0.990  # atm
T = 55 + 273 # ºC a K
R = 0.0821 # L·atm/(K·mol)
molar_mass_CO2 = 44   # g/mol
# Calcular n/V (número de moles por litro)
n_V = P / (R * T)
# Calcular la densidad en g/L
density_CO2 = n_V * molar_mass_CO2 print(density_CO2)




14
# Datos dados
P_mmHg = 779 # mmHg
T_Celsius = 62  # ºC
# Convertir la presión a atmósferas (atm) P_atm = P_mmHg / 760# Convertir la temperatura a kelvin (K)
T_kelvin = T_Celsius + 273.15
# Encontrar la masa molar del UF6
molar_mass_UF6 = (238.05 + (18.998 * 6)) # g/mol
# Calcular n/V (número de moles por litro)
n_V = P_atm / (0.0821 * T_kelvin)
# Calcular la densidad en g/L
density_UF6 = n_V * molar_mass_UF6
print(density_UF6)




15
# Datos dados
density = 7.71 # g/L
temperature_Celsius = 36  # ºC
pressure_atm = 2.88 # atm
R = 0.0821 # L·atm/(K·mol)
Vm_standard = 22.4  # L/mol
# Convertir la temperatura a kelvin (K)
temperature_K = temperature_Celsius + 273.15
# Calcular el número de moles por litro (n/V)
n_over_V = pressure_atm / (R * temperature_K)
# Calcular la masa molar
molar_mass = density / Vm_standard
# Determinar la relación de masa molar entre cloro y oxígeno mass_ratio_Cl_O = 35.45 / 16.00
mass_ratio_formula = molar_mass / mass_ratio_Cl_O
x = mass_ratio_formula / (2*35.45 + 16.00)
# Calcular la masa molar de la fórmula molecular
molar_mass_molecular = 2*x*35.45 + 16.00
# Mostrar la masa molar de la fórmula molecular y la fórmula print(format(molar_mass_molecular))
print("La fórmula molecular podría ser Cl{}_2O".format(round(x)))



16
P = 1.97  # atm
T = 40 + 273.15  # ºC a K
densidad = 3.38  # g/L
Vm = 22.4 # L/mol (volumen molar en condiciones estándar)
# Calcular n/V (número de moles por litro) n_V = P / (0.0821 * T)
# Calcular la masa molar
M = densidad / Vm print(M)



17
# Datos dados
P = 1.70  # atm
V = 0.210  # L
T = 35 + 273.15  # ºC a K
masa_g = 2.38  # g
# Calcular moles de gas
n = (P * V) / (0.0821 * T)
# Calcular la masa molar del compuesto
masa_molar = masa_g / n
# Encontrar la fórmula empírica
proporcion_Si = 0.33
proporcion_F = 0.67
# Calcular la fórmula molecular
relacion_masa_molar = masa_molar / (28.0855 + (18.9984 * 2))  # Masas molares de Si y F
# Fórmula molecular
formula_molecular = f"Si2F4" formula_molecular



18
# Datos dados
P = 1.12  # atm
V = 74.3 / 1000  # L (convertir mL a L)
T = 27 + 273.15  # K (convertir ºC a K)
masa_g = 0.0934  # g
# Calcular moles de gas
n = (P * V) / (0.0821 * T)
# Calcular la masa molar del compuesto
masa_molar = masa_g / n
# Calcular la relación de átomos de Boro (B) y Hidrógeno (H) porcentaje_B = 78.14
porcentaje_H = 21.86
moles_B = porcentaje_B / 10.811  # Masa molar de Boro moles_H = porcentaje_H / 1.008   # Masa molar de Hidrógeno
# Encontrar la fórmula empírica formula_empirica = f"B{round(moles_B)}H{round(moles_H)}"
# Calcular la fórmula molecular
masa_molar_medida = masa_molar
relacion_masa_molar = masa_molar_medida / masa_molar
# Fórmula molecular
formula_molecular = f"B2H6" formula_molecular



19
# Datos dados
P = 1 # atm (suponiendo condiciones estándar)
V_C2H2 = 7.64  # L
T = 273.15 # K (0 ºC en Kelvin)
# Convertir litros a moles de acetileno (C2H2)
n_C2H2 = (P * V_C2H2) / (0.0821 * T)
# Calcular moles de oxígeno necesarios
n_O2 = 2 * n_C2H2  # Relación estequiométrica es 1:2 entre C2H2 y O2# Convertir moles de oxígeno a litros V_O2 = (n_O2 * 0.0821 * T) / P print(V_O2)



20
# Datos dados
P_mmHg = 823 # mmHg
T_Celsius = 80  # ºC
m_NaN3 = 60.0  # g
M_NaN3 = 65.01 + 3*14.01  # Masa molar de NaN3 (g/mol)
# Convertir presión a atmósferas (atm)
P_atm = P_mmHg / 760
# Convertir temperatura a kelvin (K)
T_kelvin = T_Celsius + 273.15
# Calcular moles de NaN3
n_NaN3 = m_NaN3 / M_NaN3
# Usar la relación estequiométrica para determinar moles de N2 producidos
# Según la ecuación, 2 moles de NaN3 producen 3 moles de N2 n_N2 = (3/2) * n_NaN3
# Utilizar la ecuación de los gases ideales para calcular el volumen de N2
V_N2 = (n_N2 * 0.0821 * T_kelvin) / P_atm print(V_N2)
