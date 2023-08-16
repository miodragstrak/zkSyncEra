functions: {
    initializeProviderAndSigner() {
      // TODO: initialize provider and signer based on `window.ethereum`
    },
  
    async getGreeting() {
      // TODO: return the current greeting
      return "";
    },
  
    async getFee() {
      // TODO: return formatted fee
      return "";
    },
  
    async getBalance() {
      // Return formatted balance
      return "";
    },
    async getOverrides() {
      if (this.selectedToken.l1Address != ETH_L1_ADDRESS) {
        // TODO: Return data for the paymaster
      }
  
      return {};
    },
  