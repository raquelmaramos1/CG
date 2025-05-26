# CG e bases
print("Análise de Bases Nitrogenadas")
dna = "TTTGGAGACTGCCAGGGACCATGTTTTGCCCATTGACTATTACTTATCCAGAACCCGGGCCCCAGGCACCCAGAGGCCGCGAGCGCAGCACCTCCCGGCGCCAGTTTGCTGCTGCTGCAGCAGCAGCAGCAGCAGCAGCAGCAGCAGCAGCAGCAGCAGCAGCAGCAGCAGCAGCAGCAGCAGCAAGAGACTAGCCCCAGGCAGCAGCAGCAGCAGCAGGGTGAGGATGGTTCTCCCCAAGCCCATCGTAGAGGCCCCACAGGCTACCTGGTCCTGGATGAGGAACAGCAACCTTCACAGCCGCAGTCGGCCCTGGAGTG"

# Contagem de cada base
contagem_A = dna.count("A")
contagem_T = dna.count("T")
contagem_C = dna.count("C")
contagem_G = dna.count("G")

# Exibindo os resultados
print(f"Total de bases: {len(dna)} pb")
print(f"Adenina (A): {contagem_A}")
print(f"Timina (T): {contagem_T}")
print(f"Citosina (C): {contagem_C}")
print(f"Guanina (G): {contagem_G}")

# Extra: Cálculo de GC%
gc_percent = ((contagem_G + contagem_C) / len(dna)) * 100
print(f"Conteúdo de GC: {gc_percent:.2f}%")
