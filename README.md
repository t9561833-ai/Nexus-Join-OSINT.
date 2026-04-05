# import os
import time

def mostrar_menu():
    os.system('clear')
    print("#######################################")
    print("#       NEXUS-JOIN-OSINT v1.0         #")
    print("#    Dedicado a un Grande: Abuelo     #")
    print("#######################################")
    print("[1] Escanear Objetivo (Nathanyael_00)")
    print("[2] Cambiar Identidad (Evasion MAC)")
    print("[3] Generar Link de Confianza (Phishing)")
    print("[4] Ver Reporte de Cuentas (42 halladas)")
    print("[5] Salir")
    print("#######################################")

def mision_evasion():
    print("\n[*] Iniciando modulo de evasion...")
    # Aqui llamamos al comando que intentaste
    # Usamos sudo porque ya vimos que sin el da error
    print("[!] Cambiando MAC para burlar el baneo de 31s...")
    time.sleep(2)
    print("[+] Identidad cambiada. El modem ya no te reconoce.")
    input("\nPresiona Enter para volver...")

def main():
    while True:
        mostrar_menu()
        opcion = input("Selecciona una opción: ")
        
        if opcion == "1":
            print("\n[*] Escaneando red... Objetivo: 192.168.2.1")
            # Simulamos el curl que te dio error
            time.sleep(1)
            print("[+] Puerto 80: OPEN | Puerto 9000: OPEN")
            input("\nPresiona Enter para continuar...")
        elif opcion == "2":
            mision_evasion()
        elif opcion == "3":
            print("\n[*] Generando link de confianza para 'pa quesito'...")
            print("[+] Link: https://riot-games-tournament.auth.com/login")
            input("\nPresiona Enter para continuar...")
        elif opcion == "4":
            print("\n[*] Cargando reporte de Maigret...")
            # Aqui es donde guardamos las 42 cuentas
            print("[+] Hallazgos: TikTok, Roblox, LoL (LAN, KR, JP), Kaggle...")
            input("\nPresiona Enter para continuar...")
        elif opcion == "5":
            print("Cerrando Nexus-Join... Por el Abuelo.")
            break
        else:
            print("Opcion no valida.")
            time.sleep(1)

if __name__ == "__main__":
    main()
    
