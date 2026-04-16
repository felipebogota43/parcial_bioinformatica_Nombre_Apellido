# parcial_bioinformatica_Nombre_Apellido
Mi Parcial
fasterq-dump SRR11140744/SRR11140744.sra --split-files







plot_pi<-ggplot(d, aes(x=Fecha, y=Mutaciones))+ geom_point()+ scale_color_manual(values = c("TRUE" = "#89a9a3", "FALSE" = "#b3489d")) + theme(panel.background = element_rect(fill = "white",colour =  "black")) + mynamestheme+ ggtitle("Mutaciones de SARS-CoV")+ ylab(Mutaciones") +  xlab("Fecha")
 plot_pi<-ggplot(d, aes(x=Fecha, y=Casos_Totales))+ geom_line()+ scale_color_manual(values = c("TRUE" = "#89a9a3", "FALSE" = "#b3489d")) + theme(panel.background = element_rect(fill = "white",colour =  "black")) + mynamestheme+ ggtitle("Casos de SARS-CoV-2")+ ylab("Casos") +  xlab("Fecha")

 https://github.com/felipebogota43/parcial_bioinformatica_Nombre_Apellido/upload/main
