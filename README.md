DataSetToJSON
=============


--------------------------------
Class for Serialize DataSet
--------------------------------


-----------------------
 // Example
-----------------------


        clsJSON objJSON = new clsJSON();

        dsTest = loadDataSet();

        string json = "";

        json = objJSON.SerializeDataTable(dsTest.Tables[0]);

        Response.Write("SerializeDataTable");
        Response.Write("</BR></BR>");

        Response.Write(json);

        Response.Write("</BR></BR>");

        json = objJSON.SerializeDataSet(dsTest);

        dsTest = objJSON.GetDataSet(json);

        Response.Write("SerializeDataSet");
        Response.Write("</BR></BR>");

        Response.Write(json);



Read more: http://longbit.com.br

