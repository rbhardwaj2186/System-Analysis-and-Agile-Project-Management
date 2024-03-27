# CareConnect: Revolutionizing Healthcare Consultations

## CareConnect is a digital platform aimed at revolutionizing medication administration and healthcare consultations. This project was developed with a focus on system analysis and project management, utilizing tools such as UML, WBS, ERD, SQL, and Rest API.

### Overview
The primary goal of CareConnect is to create a comprehensive healthcare environment. It achieves this by providing a website and app that allows users to locate physicians and place medication orders.

### Key Features
Physician Locator: CareConnect includes a feature that allows users to locate physicians based on their specialty, location, and availability.

Medication Ordering: Users can place medication orders directly through the platform. This feature simplifies the process of obtaining necessary medications and ensures they are delivered in a timely manner.
[Uploading draw6.drawio…]()<mxfile host="app.diagrams.net" modified="2024-02-06T18:01:05.510Z" agent="Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/121.0.0.0 Safari/537.36" etag="u3oYJLSw0LClOe14esai" version="23.1.1" type="device">
  <diagram name="Page-1" id="FKafXlecHgtqjbSntQCs">
    <mxGraphModel dx="1050" dy="1657" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="850" pageHeight="1100" background="#D5E8D4" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="N1pPKT5EksWGm8BxFDVx-1" value="Patient" style="shape=table;startSize=30;container=1;collapsible=1;childLayout=tableLayout;fixedRows=1;rowLines=0;fontStyle=1;align=center;resizeLast=1;html=1;" vertex="1" parent="1">
          <mxGeometry x="50" y="-80" width="140" height="150" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-2" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-1">
          <mxGeometry y="30" width="140" height="30" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-3" value="PK" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;fontStyle=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-2">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-4" value="PatientID" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;fontStyle=5;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-2">
          <mxGeometry x="30" width="110" height="30" as="geometry">
            <mxRectangle width="110" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-5" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-1">
          <mxGeometry y="60" width="140" height="30" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-6" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-5">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-7" value="FirstName" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-5">
          <mxGeometry x="30" width="110" height="30" as="geometry">
            <mxRectangle width="110" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-8" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-1">
          <mxGeometry y="90" width="140" height="30" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-9" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-8">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-10" value="DOB&lt;br&gt;" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-8">
          <mxGeometry x="30" width="110" height="30" as="geometry">
            <mxRectangle width="110" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-11" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-1">
          <mxGeometry y="120" width="140" height="30" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-12" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-11">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-13" value="MedicalHistory&lt;br&gt;" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-11">
          <mxGeometry x="30" width="110" height="30" as="geometry">
            <mxRectangle width="110" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-27" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=1;exitY=0.5;exitDx=0;exitDy=0;" edge="1" parent="N1pPKT5EksWGm8BxFDVx-1" source="N1pPKT5EksWGm8BxFDVx-5" target="N1pPKT5EksWGm8BxFDVx-5">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-14" value="Medication Data" style="shape=table;startSize=30;container=1;collapsible=1;childLayout=tableLayout;fixedRows=1;rowLines=0;fontStyle=1;align=center;resizeLast=1;html=1;" vertex="1" parent="1">
          <mxGeometry x="380" y="-160" width="180" height="150" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-15" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-14">
          <mxGeometry y="30" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-16" value="PK" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;fontStyle=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-15">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-17" value="MedicationID" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;fontStyle=5;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-15">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-18" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-14">
          <mxGeometry y="60" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-19" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-18">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-20" value="MedicationName" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-18">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-21" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-14">
          <mxGeometry y="90" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-22" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-21">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-23" value="PrescriptionDate" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-21">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-24" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-14">
          <mxGeometry y="120" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-25" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-24">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-26" value="PrescriptionProvider" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-24">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-28" value="Appointment" style="shape=table;startSize=30;container=1;collapsible=1;childLayout=tableLayout;fixedRows=1;rowLines=0;fontStyle=1;align=center;resizeLast=1;html=1;" vertex="1" parent="1">
          <mxGeometry x="350" y="40" width="160" height="160" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-29" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-28">
          <mxGeometry y="30" width="160" height="30" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-30" value="PK" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;fontStyle=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-29">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-31" value="AppointmentID" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;fontStyle=5;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-29">
          <mxGeometry x="30" width="130" height="30" as="geometry">
            <mxRectangle width="130" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-32" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-28">
          <mxGeometry y="60" width="160" height="40" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-33" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-32">
          <mxGeometry width="30" height="40" as="geometry">
            <mxRectangle width="30" height="40" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-34" value="PatientID" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-32">
          <mxGeometry x="30" width="130" height="40" as="geometry">
            <mxRectangle width="130" height="40" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-35" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-28">
          <mxGeometry y="100" width="160" height="30" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-36" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-35">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-37" value="DateTime" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-35">
          <mxGeometry x="30" width="130" height="30" as="geometry">
            <mxRectangle width="130" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-38" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-28">
          <mxGeometry y="130" width="160" height="30" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-39" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-38">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-40" value="Book()" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-38">
          <mxGeometry x="30" width="130" height="30" as="geometry">
            <mxRectangle width="130" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-41" value="Doctor" style="shape=table;startSize=30;container=1;collapsible=1;childLayout=tableLayout;fixedRows=1;rowLines=0;fontStyle=1;align=center;resizeLast=1;html=1;" vertex="1" parent="1">
          <mxGeometry x="700" y="-30" width="120" height="150" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-42" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-41">
          <mxGeometry y="30" width="120" height="30" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-43" value="PK" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;fontStyle=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-42">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-44" value="DoctoriD" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;fontStyle=5;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-42">
          <mxGeometry x="30" width="90" height="30" as="geometry">
            <mxRectangle width="90" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-45" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-41">
          <mxGeometry y="60" width="120" height="30" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-46" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-45">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-47" value="CheckPatient" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-45">
          <mxGeometry x="30" width="90" height="30" as="geometry">
            <mxRectangle width="90" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-48" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-41">
          <mxGeometry y="90" width="120" height="30" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-49" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-48">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-50" value="ProvidePrescpn" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-48">
          <mxGeometry x="30" width="90" height="30" as="geometry">
            <mxRectangle width="90" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-51" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-41">
          <mxGeometry y="120" width="120" height="30" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-52" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-51">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-53" value="Designation&lt;br&gt;" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-51">
          <mxGeometry x="30" width="90" height="30" as="geometry">
            <mxRectangle width="90" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-54" value="Analytics Data" style="shape=table;startSize=30;container=1;collapsible=1;childLayout=tableLayout;fixedRows=1;rowLines=0;fontStyle=1;align=center;resizeLast=1;html=1;" vertex="1" parent="1">
          <mxGeometry x="640" y="220" width="180" height="150" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-55" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-54">
          <mxGeometry y="30" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-56" value="PK" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;fontStyle=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-55">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-57" value="ReportID" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;fontStyle=5;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-55">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-58" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-54">
          <mxGeometry y="60" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-59" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-58">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-60" value="PatientID" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-58">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-61" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-54">
          <mxGeometry y="90" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-62" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-61">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-63" value="ProviderID" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-61">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-64" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-54">
          <mxGeometry y="120" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-65" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-64">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-66" value="HealthMetrics&lt;br&gt;" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-64">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-67" value="Health Record" style="shape=table;startSize=30;container=1;collapsible=1;childLayout=tableLayout;fixedRows=1;rowLines=0;fontStyle=1;align=center;resizeLast=1;html=1;" vertex="1" parent="1">
          <mxGeometry x="20" y="130" width="180" height="150" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-68" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-67">
          <mxGeometry y="30" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-69" value="PK" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;fontStyle=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-68">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-70" value="HealthRecordID" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;fontStyle=5;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-68">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-71" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-67">
          <mxGeometry y="60" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-72" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-71">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-73" value="PatientID" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-71">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-74" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-67">
          <mxGeometry y="90" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-75" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-74">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-76" value="VisitDate" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-74">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-77" value="" style="shape=tableRow;horizontal=0;startSize=0;swimlaneHead=0;swimlaneBody=0;fillColor=none;collapsible=0;dropTarget=0;points=[[0,0.5],[1,0.5]];portConstraint=eastwest;top=0;left=0;right=0;bottom=0;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-67">
          <mxGeometry y="120" width="180" height="30" as="geometry" />
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-78" value="" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;editable=1;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-77">
          <mxGeometry width="30" height="30" as="geometry">
            <mxRectangle width="30" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-79" value="TreatmentPlans" style="shape=partialRectangle;connectable=0;fillColor=none;top=0;left=0;bottom=0;right=0;align=left;spacingLeft=6;overflow=hidden;whiteSpace=wrap;html=1;" vertex="1" parent="N1pPKT5EksWGm8BxFDVx-77">
          <mxGeometry x="30" width="150" height="30" as="geometry">
            <mxRectangle width="150" height="30" as="alternateBounds" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-80" value="" style="edgeStyle=entityRelationEdgeStyle;fontSize=12;html=1;endArrow=ERmany;endFill=0;rounded=0;entryX=1;entryY=0.5;entryDx=0;entryDy=0;startArrow=ERone;startFill=0;" edge="1" parent="1" source="N1pPKT5EksWGm8BxFDVx-67" target="N1pPKT5EksWGm8BxFDVx-2">
          <mxGeometry width="100" height="100" relative="1" as="geometry">
            <mxPoint x="210" y="140" as="sourcePoint" />
            <mxPoint x="470" y="40" as="targetPoint" />
            <Array as="points">
              <mxPoint x="200" y="120" />
              <mxPoint x="200" y="120" />
              <mxPoint x="210" y="190" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-82" value="" style="edgeStyle=segmentEdgeStyle;endArrow=ERone;html=1;curved=0;rounded=0;endSize=8;startSize=8;exitX=0.417;exitY=-0.009;exitDx=0;exitDy=0;exitPerimeter=0;entryX=0.677;entryY=-0.017;entryDx=0;entryDy=0;entryPerimeter=0;startArrow=ERone;startFill=0;endFill=0;" edge="1" parent="1" source="N1pPKT5EksWGm8BxFDVx-1" target="N1pPKT5EksWGm8BxFDVx-41">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="400" y="70" as="sourcePoint" />
            <mxPoint x="790" y="-173.2000732421875" as="targetPoint" />
            <Array as="points">
              <mxPoint x="108" y="-190" />
              <mxPoint x="781" y="-190" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-83" value="" style="edgeStyle=segmentEdgeStyle;endArrow=ERmany;html=1;curved=0;rounded=0;endSize=8;startSize=8;startArrow=ERone;startFill=0;endFill=0;" edge="1" parent="1">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="147" y="-80" as="sourcePoint" />
            <mxPoint x="448" y="40" as="targetPoint" />
            <Array as="points">
              <mxPoint x="147" y="-140" />
              <mxPoint x="310" y="-140" />
              <mxPoint x="310" y="10" />
              <mxPoint x="448" y="10" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-86" value="" style="edgeStyle=segmentEdgeStyle;endArrow=classic;html=1;curved=0;rounded=0;endSize=8;startSize=8;entryX=0.25;entryY=0;entryDx=0;entryDy=0;exitX=0.998;exitY=0.94;exitDx=0;exitDy=0;exitPerimeter=0;" edge="1" parent="1" source="N1pPKT5EksWGm8BxFDVx-24" target="N1pPKT5EksWGm8BxFDVx-41">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="560" y="20" as="sourcePoint" />
            <mxPoint x="720" y="-70" as="targetPoint" />
            <Array as="points">
              <mxPoint x="560" y="20" />
              <mxPoint x="600" y="20" />
              <mxPoint x="600" y="-80" />
              <mxPoint x="730" y="-80" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-88" value="" style="endArrow=ERmany;startArrow=ERone;html=1;rounded=0;exitX=0.75;exitY=0;exitDx=0;exitDy=0;startFill=0;endFill=0;" edge="1" parent="1" source="N1pPKT5EksWGm8BxFDVx-67">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="400" y="80" as="sourcePoint" />
            <mxPoint x="155" y="70" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-90" value="" style="endArrow=ERone;startArrow=ERone;html=1;rounded=0;entryX=0.543;entryY=1.06;entryDx=0;entryDy=0;entryPerimeter=0;startFill=0;endFill=0;exitX=0.696;exitY=-0.015;exitDx=0;exitDy=0;exitPerimeter=0;" edge="1" parent="1" source="N1pPKT5EksWGm8BxFDVx-54" target="N1pPKT5EksWGm8BxFDVx-51">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="765" y="210" as="sourcePoint" />
            <mxPoint x="450" y="30" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-91" value="" style="edgeStyle=segmentEdgeStyle;endArrow=ERoneToMany;html=1;curved=0;rounded=0;endSize=8;startSize=8;exitX=0;exitY=0.5;exitDx=0;exitDy=0;entryX=0.834;entryY=-0.015;entryDx=0;entryDy=0;entryPerimeter=0;endFill=0;startArrow=ERone;startFill=0;" edge="1" parent="1" source="N1pPKT5EksWGm8BxFDVx-55" target="N1pPKT5EksWGm8BxFDVx-1">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="370" y="290" as="sourcePoint" />
            <mxPoint x="170" y="-100" as="targetPoint" />
            <Array as="points">
              <mxPoint x="300" y="265" />
              <mxPoint x="300" y="-110" />
              <mxPoint x="167" y="-110" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-92" value="" style="edgeStyle=segmentEdgeStyle;endArrow=none;html=1;curved=0;rounded=0;endSize=8;startSize=8;exitX=1;exitY=0.5;exitDx=0;exitDy=0;entryX=0.01;entryY=-0.153;entryDx=0;entryDy=0;entryPerimeter=0;startArrow=classicThin;startFill=1;endFill=0;" edge="1" parent="1" source="N1pPKT5EksWGm8BxFDVx-74" target="N1pPKT5EksWGm8BxFDVx-48">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="250" y="230" as="sourcePoint" />
            <mxPoint x="590" y="60" as="targetPoint" />
            <Array as="points">
              <mxPoint x="280" y="235" />
              <mxPoint x="280" y="390" />
              <mxPoint x="590" y="390" />
              <mxPoint x="590" y="55" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-108" value="" style="edgeStyle=segmentEdgeStyle;endArrow=ERone;html=1;curved=0;rounded=0;endSize=8;startSize=8;entryX=0.01;entryY=0.02;entryDx=0;entryDy=0;entryPerimeter=0;startArrow=ERoneToMany;startFill=0;exitX=0.313;exitY=0;exitDx=0;exitDy=0;exitPerimeter=0;endFill=0;" edge="1" parent="1" source="N1pPKT5EksWGm8BxFDVx-28" target="N1pPKT5EksWGm8BxFDVx-45">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="400" y="30" as="sourcePoint" />
            <mxPoint x="450" y="30" as="targetPoint" />
            <Array as="points">
              <mxPoint x="400" />
              <mxPoint x="500" />
              <mxPoint x="500" y="31" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="N1pPKT5EksWGm8BxFDVx-115" value="" style="edgeStyle=segmentEdgeStyle;endArrow=ERone;html=1;curved=0;rounded=0;endSize=8;startSize=8;exitX=-0.023;exitY=0.287;exitDx=0;exitDy=0;exitPerimeter=0;endFill=0;startArrow=ERoneToMany;startFill=0;" edge="1" parent="1" source="N1pPKT5EksWGm8BxFDVx-8" target="N1pPKT5EksWGm8BxFDVx-64">
          <mxGeometry width="50" height="50" relative="1" as="geometry">
            <mxPoint x="10" as="sourcePoint" />
            <mxPoint x="630" y="350" as="targetPoint" />
            <Array as="points">
              <mxPoint x="10" y="19" />
              <mxPoint x="10" y="400" />
              <mxPoint x="370" y="400" />
              <mxPoint x="370" y="350" />
            </Array>
          </mxGeometry>
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>


Comprehensive Healthcare Environment: CareConnect aims to provide a comprehensive healthcare environment. This means that all aspects of a user’s healthcare needs, from consultations to medication administration, can be managed within the platform.

System Analysis and Project Management: The development of CareConnect was led using various system analysis and project management tools. These include UML for visualizing the system’s architecture, WBS for breaking down the project into manageable tasks, ERD for understanding the system’s data and relationships, and SQL and Rest API for managing the system’s data and interfaces.

### Usage
CareConnect can be utilized by patients seeking an efficient and comprehensive solution for managing their healthcare needs. By using the platform, patients can easily locate physicians, schedule consultations, and order medications.

### Future Work
Future enhancements to CareConnect may include expanding the database of physicians, integrating with local pharmacies for faster medication delivery, and incorporating telemedicine features for remote consultations.

Please refer to the project’s GitHub page for more detailed information and usage instructions.
