# parcial_bioinformatica_Nombre_Apellido
Mi Parcial
# Punto 1
se tranformo el archivo .sra a archivo.fastq y con eso logre calcular los Kmers con jellyfish en un sbatch luego par reducir los singletons use java en otro sbatch y por ultimo volvi a utilizar jellyfish en otro sbach par ver otraves los Kmers por utilmo utilice SPAdes  para el ensabalje y saque las estadisticas con quast.
# Punto 2
En primer lugar utilice cat para concatenra todos los archivos fasta que tenia  en el cluster luego utilice clustal para hacer el alineaineto con iqtree en sbatch hice el arbol que se ve en el link a continuacion

https://github.com/felipebogota43/parcial_bioinformatica_Nombre_Apellido/upload
Se ve que las mutaciones spike colombiana y Wuhan estan cercanamente relacionadas a diferencia de las demas mutaciones y alfa y delta estan cercanamente relacionada y Omicron no se relaciona cercanamnete con ninguna mutacion.


# Punto 3
plot_pi<-ggplot(d, aes(x=Fecha, y=Mutaciones))+ geom_point()+ scale_color_manual(values = c("TRUE" = "#89a9a3", "FALSE" = "#b3489d")) + theme(panel.background = element_rect(fill = "white",colour =  "black")) + mynamestheme+ ggtitle("Mutaciones de SARS-CoV")+ ylab(Mutaciones") +  xlab("Fecha")
 plot_pi<-ggplot(d, aes(x=Fecha, y=Casos_Totales))+ geom_line()+ scale_color_manual(values = c("TRUE" = "#89a9a3", "FALSE" = "#b3489d")) + theme(panel.background = element_rect(fill = "white",colour =  "black")) + mynamestheme+ ggtitle("Casos de SARS-CoV-2")+ ylab("Casos") +  xlab("Fecha")

https://github.com/felipebogota43/parcial_bioinformatica_Nombre_Apellido/upload/main
 Si hay una relacion entre las mutaciones y el numero de casos ya que donde hay picos en la grafica de casos tambien hay un mayor numero de mutaciones en la otra grafica.En la actualida hay un menor numero de mutaciones al igual que el numero de casos.Esto se puede interpretar de forma que en los años 2020 hata el 2024 hubo un numero mayor al promedio de mutaciones y numero de casos.
