<h1> Optimization-Metadata </h1>

<h2 align="center">Meta-data core functionalities for Hyperactive.</h2>

<br>

This package is a collection of core functionalities for the memory module in Hyperactive. It enables Hyperactive to "remember" previous evaluations, which can save significant computation time. The effect is, that every position in the search-space that has been evaluated once never needs to be evaluated again. The previous calculated score has been stored and can just be looked up instead of recalculating it.
Optimization-Metadata also enables persistent storage of python-objects in the meta-data. This means, that information about the objective-function and python-objects in the search-space can be saved and read via the dill-package.

<br>

<table>
  <tbody>
    <tr align="left" valign="center">
      <td>
        <strong>Master status:</strong>
      </td>
      <td>
        <a href="https://travis-ci.com/SimonBlanke/Optimization-Metadata">
          <img src="https://img.shields.io/travis/com/SimonBlanke/Optimization-Metadata/master?style=flat-square&logo=travis" alt="img not loaded: try F5 :)">
        </a>
        <a href="https://coveralls.io/github/SimonBlanke/Optimization-Metadata">
          <img src="https://img.shields.io/coveralls/github/SimonBlanke/Optimization-Metadata?style=flat-square&logo=codecov" alt="img not loaded: try F5 :)">
        </a>
      </td>
    </tr>
    <tr/>
    <tr align="left" valign="center">
      <td>
         <strong>Code quality:</strong>
      </td>
      <td>
        <a href="https://codeclimate.com/github/SimonBlanke/Optimization-Metadata">
        <img src="https://img.shields.io/codeclimate/maintainability/SimonBlanke/Optimization-Metadata?style=flat-square&logo=code-climate" alt="img not loaded: try F5 :)">
        </a>
        <a href="https://scrutinizer-ci.com/g/SimonBlanke/Optimization-Metadata/">
        <img src="https://img.shields.io/scrutinizer/quality/g/SimonBlanke/Optimization-Metadata?style=flat-square&logo=scrutinizer-ci" alt="img not loaded: try F5 :)">
        </a>
      </td>
    </tr>
    <tr/>    <tr align="left" valign="center">
      <td>
        <strong>Latest versions:</strong>
      </td>
      <td>
        <a href="https://pypi.org/project/hypermemory/">
          <img src="https://img.shields.io/pypi/v/Optimization-Metadata?style=flat-square&logo=PyPi&logoColor=white" alt="img not loaded: try F5 :)">
        </a>
      </td>
    </tr>
  </tbody>
</table>
