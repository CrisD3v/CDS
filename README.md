# DOCUMENTACION CDS

Esta archivo se genero con el fin de tener claro el uso de funciones para los controladores de manera estandar.

## FUNCIONES PARA USO GENERICO

#### OBTENER DATOS DB

## Funciones y Enlaces

```PHP
- getModelMapping()
- getDocumentTBArr();
- getDataTypeTableNameConsult();
- getTableName();
- getAdicionalTablesName();
- getConsultDataTable();
```

#### DATOS IMPORTANTES

```PHP
- getCurrentDateAndFinDate();
```

#### MATRICES (ARRAYS)

```PHP
- arrayGetCamps();
- getDataArrDoc();
- getDataArray();
- arrayDataProces();
```

#### STORE Y UPDATE

```PHP
- eachArrayGroupData();
- createOrUpdateAllDocsModulo();
- saveMoreDataArr();
```

## FUNCIONES VISTA

#### CREAR

```PHP
- modulo_CreateDoc();
```

#### EDITAR

```PHP
- modulo_EditDoc();
```

#### PDF

```PHP
- modulo_PdfDoc();
```

## DEFINIR STORE Y UPDATE

```PHP
  public function createOrEditModulo(Request $request)
  {
    $specificFieldsArr = ['DATOS ARRAY A'];
    $cantLoop = $request->numberLoop; // CANTIDAD DE RECORRIDOS ARRAY A

    return $this->createOrUpdateAllDocsFuncindica($request, CATIDAD DE CAMPOS EN INT, MODELODBPRINCIPAL::class, 'tabla_Array_A', $specificFieldsArr, $cantLoop, null, LIMIT ARR);
  }
```

## DESCARGAR DOCUMENTACION TECNICA y CODIGO

- [DOCUMENTACION](https://drive.google.com/file/d/1xQcpMOSKqWwEuUzpk7QEkAvyKy5a4zou/view?usp=sharing)
- [CODIGO](https://drive.google.com/file/d/1F9XpU2DwxD0_GJBS7eg09pMAtyhhkR6w/view?usp=sharing)
