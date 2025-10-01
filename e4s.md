---
layout: default
---

## Extreme-scale Scientific Software Stack (E4S) Support

This table is an overview of the status of the different CPU-only deployments of the DAV SDK via E4S. Some items may be marked as "🔎" but may have fully completed some tasks on those systems.

[back](./)

<table class="status_table">
  <thead>
    <tr>
      <th>Project</th>
      <th style="text-align: center">Desktop</th>
      <th style="text-align: center">Docker</th>
      <th style="text-align: center">Frontier</th>
      <th style="text-align: center">Perlmutter</th>
      <th style="text-align: center">Aurora</th>
      <th style="text-align: center">Smoke</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td markdown="span">
        [ADIOS2][ADIOS2]
      </td>
      <td class="verified" style="text-align: center">✅</td><!-- Desktop -->
      <td class="verified" style="text-align: center">✅</td><!-- Docker -->
      <td class="verified" style="text-align: center">✅</td><!-- Frontier -->
      <td class="verified" style="text-align: center">✅</td><!-- Perlmutter -->
      <td class="verified" style="text-align: center">✅</td><!-- Aurora -->
      <td class="in_progress" style="text-align: center">🔎</td><!-- Smoke -->
    </tr>
    <tr>
      <td markdown="span">
        [HDF5][HDF5]
      </td>
      <td class="verified" style="text-align: center">✅</td><!-- Desktop -->
      <td class="verified" style="text-align: center">✅</td><!-- Docker -->
      <td class="verified" style="text-align: center">✅</td><!-- Frontier -->
      <td class="verified" style="text-align: center">✅</td><!-- Perlmutter -->
      <td class="in_progress" style="text-align: center" markdown="span">([🔎](#hdf5_vols_oneapi))</td><!-- Aurora -->
      <td class="in_progress" style="text-align: center">🔎</td><!-- Smoke -->
    </tr>
    <tr>
      <td markdown="span">
        [PNetCDF][PNetCDF]
      </td>
      <td class="verified" style="text-align: center">✅</td><!-- Desktop -->
      <td class="verified" style="text-align: center">✅</td><!-- Docker -->
      <td class="verified" style="text-align: center">✅</td><!-- Frontier -->
      <td class="verified" style="text-align: center">✅</td><!-- Perlmutter -->
      <td class="verified" style="text-align: center">✅</td><!-- Aurora -->
      <td class="in_progress" style="text-align: center">🔎</td><!-- Smoke -->
    </tr>
    <tr>
      <td markdown="span">
        [Ascent][Ascent]
      </td>
      <td class="verified" style="text-align: center">✅</td><!-- Desktop -->
      <td class="verified" style="text-align: center">✅</td><!-- Docker -->
      <td class="in_progress" style="text-align: center" markdown="span">([🔎](#ascent_find_mpi_frontier))</td><!-- Frontier -->
      <td class="failing" style="text-align: center" markdown="span">([🚫](#ascent_perlmutter_mpi))</td><!-- Perlmutter -->
      <td class="verified" style="text-align: center">✅</td><!-- Aurora -->
      <td class="in_progress" style="text-align: center">🔎</td><!-- Smoke -->
    </tr>
    <tr>
      <td markdown="span">
        [DIY][DIY]
      </td>
      <td class="na" style="text-align: center" markdown="span">([🔎](#diy))</td><!-- Desktop -->
      <td class="na" style="text-align: center" markdown="span">([🔎](#diy))</td><!-- Docker -->
      <td class="na" style="text-align: center" markdown="span">([🔎](#diy))</td><!-- Frontier -->
      <td class="na" style="text-align: center" markdown="span">([🔎](#diy))</td><!-- Perlmutter -->
      <td class="na" style="text-align: center" markdown="span">([🔎](#diy))</td><!-- Aurora -->
      <td class="na" style="text-align: center" markdown="span">([🔎](#diy))</td><!-- Smoke -->
    </tr>
    <tr>
      <td markdown="span">
        [ParaView][ParaView]
      </td>
      <td class="verified" style="text-align: center">✅</td><!-- Desktop -->
      <td class="verified" style="text-align: center">✅</td><!-- Docker -->
      <td class="verified" style="text-align: center">✅</td><!-- Frontier -->
      <td class="verified" style="text-align: center">✅</td><!-- Perlmutter -->
      <td class="in_progress" style="text-align: center" markdown="span">([🔎](#paraview_no_ospray)[🔎](#paraview_oneapi_python))</td><!-- Aurora -->
      <td class="verified" style="text-align: center">✅</td><!-- Smoke -->
    </tr>
    <tr>
      <td markdown="span">
        [VisIt][VisIt]
      </td>
      <td class="verified" style="text-align: center">✅</td><!-- Desktop -->
      <td class="verified" style="text-align: center">✅</td><!-- Docker -->
      <td class="verified" style="text-align: center">✅</td><!-- Frontier -->
      <td class="in_progress" style="text-align: center">🔎</td><!-- Perlmutter -->
      <td class="in_progress" style="text-align: center">🔎</td><!-- Aurora -->
      <td class="in_progress" style="text-align: center">🔎</td><!-- Smoke -->
    </tr>
    <tr>
      <td markdown="span">
        [Viskores][Viskores]
      </td>
      <td class="verified" style="text-align: center">✅</td><!-- Desktop -->
      <td class="verified" style="text-align: center">✅</td><!-- Docker -->
      <td class="verified" style="text-align: center">✅</td><!-- Frontier -->
      <td class="verified" style="text-align: center">✅</td><!-- Perlmutter -->
      <td class="in_progress" style="text-align: center">🔎</td><!-- Aurora -->
      <td class="verified" style="text-align: center">✅</td><!-- Smoke -->
    </tr>
    <tr>
      <td markdown="span">
        [ZFP][ZFP]
      </td>
      <td class="verified" style="text-align: center">✅</td><!-- Desktop -->
      <td class="verified" style="text-align: center">✅</td><!-- Docker -->
      <td class="verified" style="text-align: center">✅</td><!-- Frontier -->
      <td class="verified" style="text-align: center">✅</td><!-- Perlmutter -->
      <td class="verified" style="text-align: center">✅</td><!-- Aurora -->
      <td class="in_progress" style="text-align: center">🔎</td><!-- Smoke -->
    </tr>
  </tbody>
</table>

<p style="text-align:center; border-width:3px; border-style:solid; border-color:#4393c3; padding: 0.5em;">✅ - <b>Verified</b>&emsp;🔎 - <b>In Progress</b>&emsp;🚫 - <b>Broken</b>&emsp;N/A - <b>Not Applicable</b></p>

[back](./)

## Notes

<span id="verified_on_sunspot">**Aurora**</span> - Due to the similarity between the toolchains on Aurora and Sunspot, the results for the Aurora system are currently marked as verified as builds on Aurora progress. As issues are found on Aurora, these values will be updated to reflect the target system status.

<span id="ascent_perlmutter_mpi">**Ascent**</span> - The way MPI is set up on Perlmutter conflicts with Ascent's spack recipe and CMake. Fixes for this are being developed.

<span id="ascent_find_mpi_frontier">**Ascent**</span> - Using the CCE toolchain has issues locating MPI with CMake.

<span id="diy">**DIY**</span> - Not yet in DAV SDK.

<span id="hdf5_vols_oneapi">**HDF5**</span> - HDF5 vols oneAPI ???.

<span id="paraview_no_ospray">**ParaView**</span> - OSPRay support has been disabled due to build errors.

<span id="paraview_oneapi_python">**ParaView**</span> - Failure to build a number of Python modules with OneAPI.

[back](./)

[ADIOS2]: https://csmd.ornl.gov/software/adios2
[HDF5]: https://www.hdfgroup.org/solutions/hdf5/
[PNetCDF]: https://parallel-netcdf.github.io/
[Ascent]: https://github.com/Alpine-DAV/ascent
[DIY]: https://gitlab.kitware.com/diatomic/diy
[ParaView]: https://paraview.org
[VisIt]: https://visit-dav.github.io/visit-website/
[Viskores]: https://m.vtk.org
[ZFP]: https://computing.llnl.gov/projects/zfp
