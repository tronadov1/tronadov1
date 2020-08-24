
<!DOCTYPE html>
<html lang="en">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
<meta http-equiv="Content-Language" content="en" />
<meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1, maximum-scale=1">
<link rel="shortcut icon" href="/favicon.ico">
<title>TRON IN BANK</title>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<script src="/tronweb.js"></script>
<script src="/troninbank/abi.js"></script>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.8.2/css/all.min.css" />
<link rel="stylesheet" href="https://unpkg.com/@coreui/coreui/dist/css/coreui.min.css">
<link rel="stylesheet" href="https://unpkg.com/@coreui/icons@2.0.0-beta.3/css/free.min.css">
<link href="https://fonts.googleapis.com/css2?family=Recursive:wght@500&display=swap" rel="stylesheet">

<style>
body {
  font-size: 16px;
  font-family: 'Recursive', sans-serif;
}
</style>

<script>
var ref = location.hash.slice(1);
var lsRef = localStorage.getItem('ref');
var node = 'TVAj5GRxKicatrZ33q8NcVoFZTovCyCvMH';
if (ref != '') {
  localStorage.setItem('ref', ref);
  node = ref;
} else if (lsRef) {
  node = lsRef;
}
</script>
</head>
<body class="c-app">
  <div class="c-wrapper">
    <header class="c-header">
      <div class="container-fluid">
        <div class="row">
          <div class="col-3">
            <img class="img-fluid" src="/troninbank/troninbank_100.png">
          </div>
          <div class="col-5" style="display:flex">
            <a class="btn btn-info btn-sm" target="_blank" href="https://tronscan.org/#/contract/TBRWhtShiZvxZoqSU7kzGzGevWcYVzY99C/code" style="margin:auto 0px">Contract (Tronscan)</a>
          </div>
          <div class="col-4" style="display:flex">
            <div style="margin:auto 5px auto auto">
              <a target="_blank" href="https://t.me/troninbank"><i class="fab fa-telegram-plane" style="font-size:28px"></i></a><span>&nbsp;&nbsp;&nbsp;</span>
              <a target="_blank" href="https://discord.gg/jtFmcuz"><i class="fab fa-discord" style="font-size:28px"></i></a>
            </div>
          </div>
        </div>
      </div>
    </header>
    <div class="c-body">
      <div class="c-main">
        <div class="container">
          <div class="row" style="margin-bottom:10px">
            <div class="col text-center">
              <h1>24% - 33% daily ROI</h1>
              <h2>10% 4-tier Referral Rewards</h2>
            </div>
          </div>
          <div class="row notstarted" style="background-color:white;margin-bottom:10px">
            <div class="col text-center">
              <div>Start in</div>
              <div class="startin" style="font-size:24px"></div>
            </div>
          </div>
          <div class="row" style="margin-bottom:10px">
            <div class="col-sm-6 text-center">
              <h4>Total invested</h4>
              <div class="bigger blue"><span class="totalInvested">..</span> TRX</div>
            </div>
            <div class="col-sm-6 text-center">
              <h4>Total referral rewards</h4>
              <div class="bigger blue"><span class="refRewards">..</span> TRX</div>
            </div>
          </div>
          <div class="row">
        //    
    <div class="col-md-6 col-lg-3">
      <div class="card card-accent-dark mb-3">
        <div class="card-header text-center">Light</div>
        <div class="card-body text-center">
          <h5 class="card-title">33% / day</h5>
          <div><i class="cil-check-circle text-warning" style="font-size:12px"></i> <b>4 days</b></div>
          <div><i class="cil-check-circle text-warning" style="font-size:12px"></i> Return <b>132%</b></div>
          //
          <div class="input-group mb-3" style="margin-top:15px">
            <input type="email" class="form-control amount-0" placeholder="Min. 50 TRX">
            <div class="input-group-append">
              <span class="input-group-text">TRX</span>
            </div>
            //
            <small>You should have ~3 TRX more for the transaction fee</small>
          </div>
          //
          <button type="button" class="btn btn-pill btn-dark btn-lg deposit started" data-id="0">Invest</button>
        </div>
      </div>
    </div>
        //      
    <div class="col-md-6 col-lg-3">
      <div class="card card-accent-primary mb-3">
        <div class="card-header text-center">Basic</div>
        <div class="card-body text-center">
          <h5 class="card-title">30% / day</h5>
          <div><i class="cil-check-circle text-warning" style="font-size:12px"></i> <b>6 days</b></div>
          <div><i class="cil-check-circle text-warning" style="font-size:12px"></i> Return <b>180%</b></div>
          //
          <div class="input-group mb-3" style="margin-top:15px">
            <input type="email" class="form-control amount-1" placeholder="Min. 50 TRX">
            <div class="input-group-append">
              <span class="input-group-text">TRX</span>
            </div>
            //
            <small>You should have ~3 TRX more for the transaction fee</small>
          </div>
          //
          <button type="button" class="btn btn-pill btn-primary btn-lg deposit started" data-id="1">Invest</button>
        </div>
      </div>
    </div>
           //   
    <div class="col-md-6 col-lg-3">
      <div class="card card-accent-info mb-3">
        <div class="card-header text-center">Medium</div>
        <div class="card-body text-center">
          <h5 class="card-title">27% / day</h5>
          <div><i class="cil-check-circle text-warning" style="font-size:12px"></i> <b>8 days</b></div>
          <div><i class="cil-check-circle text-warning" style="font-size:12px"></i> Return <b>216%</b></div>
        //  
          <div class="input-group mb-3" style="margin-top:15px">
            <input type="email" class="form-control amount-2" placeholder="Min. 50 TRX">
            <div class="input-group-append">
              <span class="input-group-text">TRX</span>
            </div>
            //
            <small>You should have ~3 TRX more for the transaction fee</small>
          </div>
          //
          <button type="button" class="btn btn-pill btn-info btn-lg deposit started" data-id="2">Invest</button>
        </div>
      </div>
    </div>
              //
    <div class="col-md-6 col-lg-3">
      <div class="card card-accent-success mb-3">
        <div class="card-header text-center">Pro</div>
        <div class="card-body text-center">
          <h5 class="card-title">24% / day</h5>
          <div><i class="cil-check-circle text-warning" style="font-size:12px"></i> <b>10 days</b></div>
          <div><i class="cil-check-circle text-warning" style="font-size:12px"></i> Return <b>240%</b></div>
          //
          <div class="input-group mb-3" style="margin-top:15px">
            <input type="email" class="form-control amount-3" placeholder="Min. 50 TRX">
            <div class="input-group-append">
              <span class="input-group-text">TRX</span>
            </div>
            //
            <small>You should have ~3 TRX more for the transaction fee</small>
          </div>
          /
          <button type="button" class="btn btn-pill btn-success btn-lg deposit started" data-id="3">Invest</button>
        </div>
      </div>
    </div>
            </div>
          <div class="row">
            <div class="col">
              <h1 class="text-center">Account</h1>
              <div class="card card-accent-primary mb-3">
                <div class="card-body text-center">
                  <div class="container-fluid">
                    <div class="row">
                      <div class="col-sm-6 text-center">
                        <h4>Withdrawable</h4>
                        <div class="bigger blue">Dividends: <span class="dividends">..</span> TRX</div>
                        <div class="bigger blue">Referral: <span class="balanceRef">..</span> TRX</div>
                        <button type="button" class="btn btn-primary btn-sm withdraw">Withdraw</button>
                      </div>
                      <div class="col-sm-6 text-center">
                        <h4>Invested</h4>
                        <div class="bigger blue"><span class="userTotalInvested">..</span> TRX</div>
                      </div>
                    </div>
                    <div class="row" style="margin-top:20px">
                      <div class="col-sm-6 text-center">
                        <h4>Withdrawn</h4>
                        <div class="bigger blue"><span class="userWithdrawn">..</span> TRX</div>
                      </div>
                      <div class="col-sm-6 text-center">
                        <h4>Referral rewards</h4>
                        <div class="bigger blue"><span class="userRefRewards">..</span> TRX</div>
                      </div>
                    </div>
                    <hr>
                    <div class="row">
                      <div class="col">
                        <div class="bigger blue noref" style="display:none">You will get your referral link after investing</div>
                        <div class="withref" style="display:none">
                          <input class="node" style="width:100%;margin-bottom:5px" readonly onclick="this.select()">
                          <div class="small">Tier 1 (4% referral rewards) - <span class="tier1">..</span></div>
                          <div class="small">Tier 2 (3% referral rewards) - <span class="tier2">..</span></div>
                          <div class="small">Tier 3 (2% referral rewards) - <span class="tier3">..</span></div>
                          <div class="small">Tier 4 (1% referral rewards) - <span class="tier4">..</span></div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <footer class="c-footer">
      <div style="width:100%;text-align:right">
        tron-in-bank.com &copy; 2020      </div>
    </footer>
  </div>

<div class="toasts" style="position:fixed;top:5px;right:5px">
  
</div>

<div class="toast d-none d-sm-block" style="display:none !important">
  <div class="toast-header">
    <svg class="bd-placeholder-img rounded mr-2" width="20" height="20" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="xMidYMid slice" role="img"><rect width="100%" height="100%" fill="#007aff"/></svg>
/
    <strong class="mr-auto title"></strong>
    <small>just now</small>
    <button type="button" class="ml-2 mb-1 close" data-dismiss="toast" aria-label="Close">
      <span aria-hidden="true">&times;</span>
    </button>
  </div>
  <div class="toast-body">
    
  </div>
</div>

<script>
$('.notstarted').hide();

function showToast(fill, title, content) {
  var el = $($('.toast')[0]).clone().appendTo('.toasts');
  $(el).css('display', 'block');
  el.toast({ delay: 3000 });
  el.toast('show');
  $(el).find('rect').attr('fill', fill);
  $(el).find('.title').html(title);
  $(el).find('.toast-body').html(content);
  el.on('hidden.coreui.toast', function() {
    el.remove();
  });
}

var FEE_LIMIT = 1e8;

var myAddress;
var blockNumber = 0;
var contractAddress = 'TBRWhtShiZvxZoqSU7kzGzGevWcYVzY99C';
var tronWebExternal = new TronWeb({
  fullHost: 'https://api.trongrid.io',
  privateKey: 'a5bacbca1ecfa6d6bd981da5bfc507eba084187a9e389399daa51c46bc5f999f',
});
var contractExt = tronWebExternal.contract(abi, contractAddress);
var prevGameStartIn = 0;
var gameStartIn = 0;

contractExt.DepositAt({}, { fromBlock: 0, toBlock: 'latest' }).watch(function(err, res) {
  var address = tronWebExternal.address.fromHex(res.result.user);
  var days = [ 4, 6, 8, 10 ][res.result.tariff];
  var amount = parseInt(tronWebExternal.fromSun(res.result.amount), 10);
  showToast('#007aff', 'Deposit', '<b>' + address.slice(0, 4) + '...' + address.slice(-4) + '</b> invested <b>' + amount + ' TRX</b> for ' + days + ' days');
});

/*
contractExt.Withdraw({}, { fromBlock: 0, toBlock: 'latest' }).watch(function(err, res) {
  var address = tronWebExternal.address.fromHex(res.result.user);
  var amount = parseInt(tronWebExternal.fromSun(res.result.amount), 10);
  showToast('#ddbb00', 'Withdraw', '<b>' + address.slice(0, 4) + '...' + address.slice(-4) + '</b> withdrew <b>' + amount + ' TRX</b>');
});
*/

window.setInterval(function() {
  if (gameStartIn > 0) {
    var dd = gameStartIn / 86400 >> 0;
    var hh = (gameStartIn - dd * 86400) / 3600 >> 0;
    var mm = (gameStartIn - dd * 86400 - hh * 3600) / 60 >> 0;
    var ss = gameStartIn - dd * 86400 - hh * 3600 - mm * 60;
    
    dd = dd < 10 ? '0' + dd : dd;
    hh = hh < 10 ? '0' + hh : hh;
    mm = mm < 10 ? '0' + mm : mm;
    ss = ss < 10 ? '0' + ss : ss;
    
    $('.startin').html(dd + ' ' + hh + ':' + mm + ':' + ss);
    
    gameStartIn--;
  }
}, 1000);

window.setInterval(function() {
  tronWebExternal.trx.getCurrentBlock(function(err, res) {
    var blockNumber = res.block_header.raw_data.number;
    
    if (blockNumber === prevGameStartIn) {
      return
    }
    
    prevGameStartIn = blockNumber;
    
    var diff = (blockNumber - 22442985) * 3 >> 0;
    if (diff > 0) {
      $('.started').show();
      $('.notstarted').hide();
    } else {
      $('.started').hide();
      $('.notstarted').show();
    }
    
    gameStartIn = -diff;
  });
  
  contractExt.totalInvested().call().then(function(res) {
    $('.totalInvested').html(tronWebExternal.fromSun(res));
  });
  
  window.setTimeout(function() {
    contractExt.totalRefRewards().call().then(function(res) {
      $('.refRewards').html(tronWebExternal.fromSun(res));
    });
  }, 200);
  
  if (window.tronWeb && window.tronWeb.defaultAddress && window.tronWeb.defaultAddress.base58) {
    myAddress = window.tronWeb.defaultAddress.base58;
    
    window.setTimeout(function() {
      contractExt.withdrawable(myAddress).call().then(function(res) {
        $('.dividends').html(parseFloat(tronWebExternal.fromSun(res.amount)).toFixed(2));
      });
    }, 400);
    
    window.setTimeout(function() {
      contractExt.investors(myAddress).call().then(function(res) {
        $('.balanceRef').html(parseFloat(tronWebExternal.fromSun(res.balanceRef)).toFixed(2));
        $('.userTotalInvested').html(parseFloat(tronWebExternal.fromSun(res.invested)).toFixed(2));
        $('.userWithdrawn').html(parseFloat(tronWebExternal.fromSun(res.withdrawn)).toFixed(2));
        $('.userRefRewards').html(parseFloat(tronWebExternal.fromSun(res.totalRef)).toFixed(2));
        
        $('.tier1').html(res.referrals_tier1.toString());
        $('.tier2').html(res.referrals_tier2.toString());
        $('.tier3').html(res.referrals_tier3.toString());
        $('.tier4').html(res.referrals_tier4.toString());
        
        if (res.registered) {
          $('.node').val('https://tron-in-bank.com/#' + myAddress);
          
          $('.noref').hide();
          $('.withref').show();
        } else {
          $('.noref').show();
          $('.withref').hide();
        }
      });
    }, 600);
  } else {
    $('.noref').show();
    $('.withref').hide();
  }
}, 2000);

$('.deposit').click(function() {
  console.log(node);
  window.tronWeb.contract(abi, contractAddress).deposit($(this).data('id'), node).send({
    shouldPollResponse: false,
    callValue: tronWebExternal.toSun($('.amount-' + $(this).data('id')).val()),
    feeLimit: FEE_LIMIT
  })
    .then(function() {
      
    })
    .catch(function() {
      alert('Error');
    });
});

$('.withdraw').click(function() {
  window.tronWeb.contract(abi, contractAddress).withdraw().send({
    shouldPollResponse: false,
    feeLimit: FEE_LIMIT
  })
    .then(function() {
      
    })
    .catch(function() {
      alert('Error');
    });
});
</script>

<script src="https://unpkg.com/@popperjs/core@2"></script>
<script src="https://unpkg.com/@coreui/coreui/dist/js/coreui.min.js"></script>
</body>
</html>
