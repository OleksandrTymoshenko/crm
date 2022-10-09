<template>
  <div>
    <div class="page-title">
      <h3>Check</h3>

      <button class="btn waves-effect waves-light btn-small">
        <i class="material-icons">refresh</i>
      </button>
    </div>

    <div class="row">
      <div class="col s12 m6 l4">
        <div class="card light-blue bill-card">
          <div class="card-content white-text">
            <span class="card-title">Currency account</span>

            <p class="currency-line">
              <span>12.0</span>
            </p>
          </div>
        </div>
      </div>

      <div class="col s12 m6 l8">
        <div class="card orange darken-3 bill-card">
          <div class="card-content white-text">
            <div class="card-header">
              <span class="card-title">Exchange Rates</span>
            </div>
            <table>
              <thead>
                <tr>
                  <th>Currency</th>
                  <th>Rates</th>
                  <th>Data</th>
                </tr>
              </thead>

              <tbody>
                <tr>
                  <td>UAH</td>
                  <td>12121</td>
                  <td>12.12.12</td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default { name: "Home-view" };
</script>
