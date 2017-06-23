# GML-Catastral
GML Catastral Multipolígono

<!-- GML Catastral Multipolígono  -->
<!-- Recomendaciones: el gml ID debe coincidir en todos los campos que lo referencian, las coordenadas deben figurar en sentido destrógiro (agujas de relog), no utilizar acentos-->
<?xml version="1.0" encoding="utf-8"?>
<gml:FeatureCollection xmlns:gml="http://www.opengis.net/gml/3.2" xmlns:gmd="http://www.isotc211.org/2005/gmd" xmlns:ogc="http://www.opengis.net/ogc" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:cp="urn:x-inspire:specification:gmlas:CadastralParcels:3.0" xmlns:base="urn:x-inspire:specification:gmlas:BaseTypes:3.2" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation="urn:x-inspire:specification:gmlas:CadastralParcels:3.0 http://inspire.ec.europa.eu/schemas/cp/3.0/CadastralParcels.xsd" gml:id="ES.LOCAL.CP.1">
   <gml:featureMember>   
   <!-- Sustituir "1A" por nombre de geometría EJ.: NEW_PARCEL -->
      <cp:CadastralParcel gml:id="ES.LOCAL.CP.1A">      
   <!-- Sustituir "AAA" por área en m2. Redondear a la baja hasta .49 y al alza desde .50. No utilizar decimales -->   
         <cp:areaValue uom="m2">AAA</cp:areaValue>
         <cp:beginLifespanVersion xsi:nil="true" nilReason="other:unpopulated"></cp:beginLifespanVersion>
         <cp:geometry>          
   <!-- Indicar sistema de Srid sustituyendo EPSG::25830 -->
   <!-- Sustituir "1A" por nombre de geometría EJ.: NEW_PARCEL -->   
           <gml:MultiSurface gml:id="MultiSurface_ES.LOCAL.CP.1A" srsName="urn:ogc:def:crs:EPSG::25830"> 
             <gml:surfaceMember>             
   <!-- Indicar sistema de Srid sustituyendo EPSG::25830 --> 
   <!-- Sustituir "1A" por nombre de geometría EJ.: NEW_PARCEL -->
               <gml:Surface gml:id="Surface_ES.LOCAL.CP.1A" srsName="urn:ogc:def:crs:EPSG::25830">
                  <gml:patches>
                    <gml:PolygonPatch>
                      <gml:exterior>
                        <gml:LinearRing>
                          <gml:posList srsDimension="2">                          
    <!-- Importamos aqui las coordenadas. Al tratarse de un polígono el primer nodo debe abrir y cerrar la ExteriorRing --> 
                          x1 y1
                          x2 y2 
                          x3 y3
                          (...)
                          x1 y1
                          </gml:posList>
                        </gml:LinearRing>
                      </gml:exterior>
                    </gml:PolygonPatch>
                  </gml:patches>
                </gml:Surface>
              </gml:surfaceMember>
            </gml:MultiSurface>
         </cp:geometry>
         <cp:inspireId>
           <base:Identifier>           
<!-- Sustituir "1A" por nombre de geometría EJ.: NEW_PARCEL -->
             <base:localId>1A</base:localId>
             <base:namespace>ES.LOCAL.CP</base:namespace>
           </base:Identifier>
         </cp:inspireId>
         <cp:label/>
         <cp:nationalCadastralReference/>
      </cp:CadastralParcel>
   </gml:featureMember>
</gml:FeatureCollection>
